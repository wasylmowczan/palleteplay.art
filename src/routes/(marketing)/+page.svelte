<script lang="ts">
  import { WebsiteName } from "./../../config"
  import { page } from "$app/stores"

  const features = [
    {
      name: "",
      description: '"Super Sonic in the empty room"',
      linkText: "Docs",
      newPage: true,
      imgContent: "/images/sonic.png",
    },
    {
      name: "",
      link: "/login",
      description: '"Spiderman in the city"',
      imgContent: "/images/spiderman.png",
    },
    {
      name: "",
      link: "/pricing",
      description: '"Tom and Jerry"',
      imgContent: `/images/tom and jerry.png`,
    },
    {
      name: "",
      link: "/blog",
      description: '"Pokemon"',
      imgContent: `/images/pokemon.png`,
    },
    {
      name: "",
      link: "/pricing",
      description: '"Paw Patrol chasing cars"',
      imgContent: "/images/patrol.png",
    },
    {
      name: "",
      link: "/account/billing",
      description: '"Sleeping cat in the bed"',
      imgContent: "/images/cat.png",
    },
    {
      name: "",
      link: "/account/settings",
      description: '"Field with flowers"',
      imgContent: "/images/flowers.png",
    },
    {
      name: "",
      link: "/contact_us",
      description: '"Dog in the Moon"',
      imgContent: `/images/dog.png`,
    },
    {
      name: "",
      newPage: true,
      linkText: "Docs",
      link: "",
      description: '"Batman playing football"',
      imgContent: `/images/batman.png`,
    },
    {
      name: "",
      description: '"Iron Man"',
      imgContent: "/images/ironman.png",
    },
    {
      name: "",
      description: '"Captain Marvel in Space"',
      newPage: true,
      link: "",
      imgContent: "/images/marvel.png",
    },
    {
      name: "",
      description: '"Disney Donald Duck in Paris"',
      imgContent: "/images/duck.png",
    },
    {
      name: "",
      description: '"Chicken businessman"',
      newPage: true,
      linkText: "Docs",
      link: "",
      imgContent: "/images/chicken.png",
    },
    {
      name: "",
      description: '"Ninja Warrior"',
      imgContent: "/images/ninja.png",
    },
    {
      name: "",
      description: '"Birds in the space"',
      linkText: "Docs",
      newPage: true,
      link: "",
      imgContent: "/images/birds.png",
    },
  ]
</script>

<svelte:head>
  <title>{WebsiteName}</title>
  <meta
    name="description"
    content="{WebsiteName} is your go-to app for creating endless fun and creativity for children with customizable coloring pages. Whether you're a parent, teacher, or guardian, {WebsiteName} offers a unique and engaging platform for unleashing imagination and artistic expression in young minds."
  />
  <meta
    name="keywords"
    content="coloring pages, coloring, pages, children, kids, fun, creativity, imagination, artistic expression, parent, teacher, guardian, paletteplay, palette, play, art, app, platform, unique, engaging, unleash, young minds, Coloring Page Generator, Coloring Page, Generator, PalettePlay, PalettePlay.art, PalettePlay art, Palette Play"
  />
  <meta property="og:type" content="website" />
  <meta
    property="og:title"
    content="Coloring Page Generator for Your Kids | PalettePlay.art"
  />
  <meta
    property="og:image"
    content="https://esqjyohxjmwmzihjeowq.supabase.co/storage/v1/object/public/assets/ogimage.png"
  />
  <meta property="og:url" content={$page.url.href} />
  <meta
    name="twitter:card"
    content="https://esqjyohxjmwmzihjeowq.supabase.co/storage/v1/object/public/assets/ogimage.png"
  />
  <meta name="twitter:creator" content="@WasylMowczan" />
  <link rel="canonical" href={$page.url.href} />
</svelte:head>

<!-- 1 section Header-->
<div class="hero min-h-[40vh]">
  <div class="hero-content text-center py-12">
    <div class="max-w-3xl">
      <div class="md:text-3xl">👶 ➕ 🎨 🟰 🥳</div>

      <div
        class="text-4xl md:text-6xl font-bold px-2"
        style="line-height: 1.2;"
      >
        Generate and print
        <span
          class="underline decoration-secondary decoration-4 md:decoration-[6px]"
          >coloring pages</span
        >
        <!-- <span
          class="underline decoration-secondary decoration-4 md:decoration-[6px]"
          ></span
        >, and -->
        <!-- <span
          class="underline decoration-secondary decoration-4 md:decoration-[6px]"
          >free to host</span
        > -->
        <span> your children really enjoy</span>
      </div>
      <br />
      <button class="btn">
        Over
        <div class="badge badge-secondary">10,000 pages created!</div>
      </button>
      <!-- <div class="stats shadow">
        <div class="stat">
          <div class="stat-title">Overs</div>
          <div class="stat-value">1,000</div>
          <div class="stat-desc">pages created!</div>
        </div>
      </div> -->
      <br />
      <br />
      <!-- <div class="mt-6 md:mt-10 text-sm md:text-lg"> TODO: add free collections her
        Explore free collections <a
          href="https://kit.svelte.dev"
          class="link font-bold"
          target="_blank">SvelteKit</a
        >,
        <a href="https://supabase.com" class="link font-bold" target="_blank"
          >Supabase</a
        >,
        <a href="https://stripe.com" class="link font-bold" target="_blank"
          >Stripe</a
        >,
        <a href="https://tailwindcss.com" class="link font-bold" target="_blank"
          >Tailwind</a
        >,
        <a href="https://daisyui.com" class="link font-bold" target="_blank"
          >DaisyUI</a
        >, and
        <a
          href="https://www.postgresql.org"
          class="link font-bold"
          target="_blank">Postgres</a
        >
      </div> -->
      <div class="mt-6 md:mt-2">
        <a href="/login/sign_up">
          <button class="btn btn-primary btn-sm px-6">★ Get started</button>
        </a>
        <a href="/login/sign_in">
          <button class="btn btn-outline btn-primary btn-sm px-6 mt-3 mx-2"
            >or Login</button
          >
        </a>
      </div>
    </div>
  </div>
</div>

<div class="max-w-[90%] lg:max-w-screen-xl mx-auto mb-16">
  <h2 class="text-center mb-4 text-2xl font-bold text-slate-700">
    Featured on
  </h2>
  <div
    class="flex items-center flex-col space-y-4 md:flex-row md:flex-wrap justify-center md:space-x-8 md:items-baseline filrer grayscale hover:grayscale-0 transition-all duration-300 ease-in-out"
  >
    <a
      href="https://www.producthunt.com/posts/palleteplay-art?embed=true&utm_source=badge-featured&utm_medium=badge&utm_souce=badge-palleteplay&#0045;art"
      target="_blank"
      ><img
        src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=461246&theme=light"
        alt="PalletePlay&#0046;art&#0032; - Coloring&#0032;page&#0032;generator&#0032;for&#0032;kids&#0046; | Product Hunt"
        style="width: 250px; height: 54px;"
        width="250"
        height="54"
      /></a
    >
    <a href="https://dang.ai/" target="_blank"
      ><img
        src="https://cdn.prod.website-files.com/63d8afd87da01fb58ea3fbcb/6487e2868c6c8f93b4828827_dang-badge.png"
        alt="Dang.ai"
        style="width: 150px; height: 54px;"
        width="150"
        height="54"
      /></a
    >
    <a href="https://saasaitools.com/?ref=badge" target="_blank">
      <img
        src="https://saasaitools.com/storage/2023/12/badge-light.webp"
        alt="SaaS AI Tools"
        width="264"
      />
    </a>
    <!-- WebCurate Spotlight -->
    <a href="https://webcurate.co/p/paletteplay-art" target="_blank"
      ><img
        src="https://webcurate.co/assets/images/webcurate-featured-badge.svg"
        alt="PalettePlay.art Featured on WebCurate"
        style="max-width: 250px; max-height: 54px;"
      /></a
    >
  </div>
</div>

<!-- 2 section - How it works -->
<div class="hero min-h-[10vh] mt-12">
  <div class="hero-content text-center pb-16 pt-4 px-4">
    <div class="max-w-lg">
      <div
        class="text-3xl md:text-5xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent mt-4"
      >
        How it works
      </div>
      <div
        class="flex flex-col lg:flex-row mt-8 gap-6 place-content-center content-center"
      >
        <div class="hidden md:block">
          <a href="/" target="_blank" class="link">
            <!-- // TODO: add link to YouTube video -->
            <div class="mockup-browser border">
              <div class="mockup-browser-toolbar">
                <div class="input" style="background:#eee;">
                  https://paletteplay.art
                </div>
              </div>
              <div class="flex justify-center">
                <video class="aspect-[1920/1080]" controls>
                  <source src="/video/Demo.mp4" type="video/mp4" />
                  <track kind="captions" />
                  Your browser does not support the video tag.
                </video>
              </div>
            </div>
          </a>
        </div>
        <!-- <div class="md:hidden">
          <a href="https://criticalmoments.io" target="_blank" class="link">
            <div class="card shadow-xl border overflow-hidden">
              <img
                alt="Screenshot of criticalmoments.io homepage"
                class="aspect-[2044/1242]"
                src="/images/example-home.png"
              />
            </div></a
          >
        </div> -->
        <div
          class="min-w-[270px] lg:min-w-[420px] flex mt-6 lg:mt-0 place-content-center content-center"
        >
          <div class="my-auto text-center">
            <div class="px-4 text-lg md:text-xl">
              Got an <span class="font-bold whitespace-nowrap">idea</span> for a
              coloring page that you just can't find anywhere else? Here you can
              create any coloring page from your imagination 🧠.
            </div>
            <div class="px-4 mt-6 text-lg md:text-xl text-start">
              <span class="font-bold whitespace-nowrap">1.</span> Create an
              account:
              <a
                href="/login/sign_up"
                target="_blank"
                class="link font-bold whitespace-nowrap">sign up</a
              >.<br />
              <span class="font-bold whitespace-nowrap">2.</span> Enter your
              prompt into the text box. <br />
              <span class="font-bold whitespace-nowrap">3.</span> Wait a few
              seconds for your image. <br />
              <span class="font-bold whitespace-nowrap">4.</span> Click download
              to save it and print later. <br />
              <span class="font-bold whitespace-nowrap">5.</span> Enjoy your
              coloring page 🥳 <br />
            </div>
            <!-- <div class="mt-4 text-large">
              <a href="https://criticalmoments.io" target="_blank">
                <button class="btn btn-primary btn-wide mt-3"
                  >See it in Action</button
                >
              </a>
            </div> -->
          </div>
        </div>
      </div>
    </div>
  </div>
</div>

<!-- 3 section - Examples -->
<div class="min-h-[60vh]">
  <div class="pt-20 pb-8 px-7">
    <div class="max-w-lg mx-auto text-center">
      <div
        class="text-2xl md:text-5xl font-bold bg-clip-text text-transparent bg-gradient-to-r from-primary to-accent"
      >
        Explore example prompts and pages
      </div>
      <div class="mt-6 text-l font-bold">
        Not sure what to try? Some example prompts with images are below. The
        best images incorporate one subject, a setting, and a style. For
        example:
        <span
          class="underline decoration-secondary decoration-[3px] md:decoration-[px]"
        >
          Santa Claus with Presents
        </span>
      </div>
    </div>

    <div
      class="flex gap-6 mt-12 max-w-[1064px] mx-auto place-content-center flex-wrap"
    >
      {#each features as feature}
        <div class="card bg-white w-[270px] min-h-[300px] flex-none shadow-xl">
          <div class="card-body items-center text-center p-[24px] pt-[32px]">
            <div>
              <img src={feature.imgContent} alt={feature.name} />
            </div>
            <!-- <h2 class="card-title">
              {feature.name}
            </h2> -->
            <p class="text-m">
              {feature.description}
            </p>
            <!-- {#if feature.link}
              <a
                href={feature.link}
                class="pb-4"
                target={feature.newPage ? "_blank" : ""}
              >
                <button
                  class="btn btn-xs btn-outline rounded-full btn-primary min-w-[100px]"
                  >{feature.linkText ? feature.linkText : "Try It"}</button
                >
              </a>
            {/if} -->
          </div>
        </div>
      {/each}
    </div>
  </div>
</div>
