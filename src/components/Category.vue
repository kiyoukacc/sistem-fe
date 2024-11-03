<template>
     <section data-layername="blogCategoryHero" class="flex flex-col text-base text-center text-gray-800">
      <header data-layername="background" class="flex flex-col justify-center items-center p-20 w-full bg-purple-50 max-md:px-5 max-md:max-w-full">
        <div class="flex flex-col items-center max-w-full w-[472px]">
          <h1 data-layername="business" class="text-6xl font-bold tracking-tighter leading-none max-md:text-4xl">
            Business
          </h1>
          <p data-layername="loremIpsumDolorSitAmetConsecteturAdipiscingElitSedDoEiusmodTemporIncididuntUtLabore" class="self-stretch mt-4 leading-7 text-zinc-500 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore.
          </p>
          <nav data-layername="blogBusiness" class="mt-8 font-medium leading-none uppercase tracking-[3px]" aria-label="breadcrumb">
            <a href="/blog" class="hover:underline focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">Blog</a>
            <span aria-hidden="true"> &gt; </span>
            <a href="/blog" class="hover:underline focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500" aria-current="page">Business</a>
          </nav>
        </div>
      </header>
    </section>
    <section class="flex flex-col items-center p-10 w-full text-base text-gray-800 bg-white">
      <div class="flex flex-row gap-5 w-full max-w-7xl">
        <!-- Main Content -->
        <main class="w-3/4">
          <!-- Article List -->
          <div class="space-y-8">
            <article class="flex gap-5">
              <img src="@/assets/images/misc/blog/blog2.png" alt="Article thumbnail" class="w-1/3 object-cover aspect-[4/3]">
              <div class="w-2/3 flex flex-col justify-center">
                <span class="text-amber-500 font-semibold uppercase">Business</span>
                <h2 class="text-2xl font-bold mt-2">Top 6 free website mockup tools 2022</h2>
                <p class="text-gray-500 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5">
              <img src="@/assets/images/misc/blog/blog2.png" alt="Article thumbnail" class="w-1/3 object-cover aspect-[4/3]">
              <div class="w-2/3 flex flex-col justify-center">
                <span class="text-amber-500 font-semibold uppercase">Business</span>
                <h2 class="text-2xl font-bold mt-2">Step-by-step guide to choosing great font pairs</h2>
                <p class="text-gray-500 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5">
              <img src="@/assets/images/misc/blog/blog2.png" alt="Article thumbnail" class="w-1/3 object-cover aspect-[4/3]">
              <div class="w-2/3 flex flex-col justify-center">
                <span class="text-amber-500 font-semibold uppercase">Business</span>
                <h2 class="text-2xl font-bold mt-2">Ten free Google fonts that you should use</h2>
                <p class="text-gray-500 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
  
            <article class="flex gap-5">
              <img src="@/assets/images/misc/blog/blog2.png" alt="Article thumbnail" class="w-1/3 object-cover aspect-[4/3]">
              <div class="w-2/3 flex flex-col justify-center">
                <span class="text-amber-500 font-semibold uppercase">Business</span>
                <h2 class="text-2xl font-bold mt-2">What did I learn from doing 50+ design sprints?</h2>
                <p class="text-gray-500 mt-2">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec.</p>
              </div>
            </article>
          </div>
        </main>
  
        <!-- Sidebar -->
        <aside class="w-1/4 space-y-10">
          <!-- Categories -->
          <section>
            <h3 class="text-xl font-bold">Categories</h3>
            <div class="mt-4 space-y-3">
              <button class="hover:bg-blue-500 hover:text-white active:bg-blue-700 active:text-white active:font-bold transition duration-150 ease-in-out flex items-center gap-4 w-full p-5 border border-gray-300 rounded-md">
                <img src="@/assets/images/logo/startup.png" alt="Startup icon" class="w-5 h-5 object-contain">
                <span class="font-bold ">Startup</span>
              </button>

              <button class="hover:bg-blue-500 hover:text-white active:bg-blue-700 active:text-white active:font-bold transition duration-150 ease-in-out flex items-center gap-4 w-full p-4 border border-gray-300 rounded-md">
                <img src="@/assets/images/logo/business.png" alt="Business icon" class="w-8 h-8 object-contain">
                <span class="font-bold">Business</span>
              </button>
              <button class="hover:bg-blue-500 hover:text-white active:bg-blue-700 active:text-white active:font-bold transition duration-150 ease-in-out flex items-center gap-4 w-full p-4 border border-gray-300 rounded-md">
                <img src="@/assets/images/logo/ekonomi.png" alt="Economy icon" class="w-8 h-8 object-contain">
                <span class="font-bold">Economy</span>
              </button>
              <button class="hover:bg-blue-500 hover:text-white active:bg-blue-700 active:text-white active:font-bold transition duration-150 ease-in-out flex items-center gap-4 w-full p-4 border border-gray-300 rounded-md">
                <img src="@/assets/images/logo/teknologi.png" alt="Technology icon" class="w-8 h-8 object-contain">
                <span class="font-bold">Technology</span>
              </button>
            </div>
          </section>
  
          <!-- Tags -->
          <section>
            <h3 class="text-xl font-bold mt-8">All Tags</h3>
            <div class="flex flex-wrap gap-3 mt-4">
              <button class="px-4 py-2 border border-gray-300 rounded-full">Business</button>
              <button class="px-4 py-2 border border-gray-300 rounded-full">Experience</button>
              <button class="px-4 py-2 border border-gray-300 rounded-full">Screen</button>
              <button class="px-4 py-2 border border-gray-300 rounded-full">Technology</button>
              <button class="px-4 py-2 border border-gray-300 rounded-full">Marketing</button>
              <button class="px-4 py-2 border border-gray-300 rounded-full">Life</button>
            </div>
          </section>
        </aside>
      </div>
    </section>
  </template>
  
  <style scoped>
  .builder-component {
    max-width: none !important;
  }
  </style>