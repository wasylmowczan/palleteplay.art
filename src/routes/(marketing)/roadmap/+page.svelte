<script lang="ts">
  import { onMount } from "svelte"

  onMount(() => {
    const script = document.createElement("script")
    script.src = "https://features.vote/widget/widget.js"
    script.setAttribute("slug", "paletteplay")
    script.setAttribute("color_mode", "light")
    script.setAttribute("user_id", "<Optional>")
    script.setAttribute("user_email", "<Optional>")
    script.setAttribute("user_name", "<Optional>")
    script.setAttribute("img_url", "<Optional>")
    script.setAttribute("user_spend", "<Optional>")
    script.setAttribute(
      "onload",
      "window.loadVotingBoard('your-container-id-here')",
    )
    document.body.appendChild(script)
  })
</script>

<div class="min-h-[70vh] pb-8 pt-[5vh] px-4">
  <div id="your-container-id-here"></div>
</div>
