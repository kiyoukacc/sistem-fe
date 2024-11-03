<script setup>

</script>

<template>
  <!-- Hero Section -->
  <section class="hero-section relative text-white min-h-[720px]">
    <img loading="lazy"
      src="@/assets/images/misc/home/cover.png"
      alt="Hero background image" class="object-cover absolute inset-0 size-full" />
    <div class="relative flex flex-col items-start px-20 py-40 w-full max-md:px-5 max-md:py-24">
      <span class="font-semibold leading-none uppercase tracking-[3px]">
        <span class="font-medium">Posted on </span>
        <span class="font-black">startup</span>
      </span>
      <h1 class="mt-6 text-6xl tracking-tighter leading-[64px] w-[803px] max-md:max-w-full max-md:text-4xl max-md:leading-[51px]">
        Step-by-step guide to choosing great font pairs
      </h1>
      <div class="mt-6 leading-7 text-white">
        By <a href="#" class="text-blue-600 hover:underline">James West</a> | May 23, 2022
      </div>
      <p class="mt-4 leading-7 w-[599px] max-md:max-w-full">
        Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        Excepteur sint occaecat cupidatat non proident.
      </p>
      <button class="gap-3 px-12 py-4 mt-12 mb-0 text-lg leading-none bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 max-md:px-5 max-md:mt-10 max-md:mb-2.5" tabindex="0">
        Read More >
      </button>
    </div>
  </section>

  <!-- Featured Posts Section -->
  <section class="featured-posts px-20 mt-32 max-md:px-5 max-md:mt-10 ">
    <div class="flex justify-between items-center mb-8">
      <h2 class="text-4xl font-bold tracking-tighter text-gray-800">Featured Post</h2>
      <div class="flex items-center gap-40">
        <h3 class="text-4xl font-bold tracking-tighter text-gray-800 ml-[-25%] ">All Posts</h3>
        <a href="#" class="text-base leading-7 ml-[20%] text-amber-300 hover:underline">View All</a>
      </div>
    </div>

    <div class="grid grid-cols-5 gap-5 max-md:cols-1 ">
      <article class="col-span-3 p-8 shadow">
        <img loading="lazy" src="@/assets/images/misc/home/featured.png"
          alt="Featured post image" class="w-full aspect-[1.9] object-cover" />
         <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
              By <span class="text-amber-300">John Doe</span> | May 23, 2022
            </time>
        <h3 class="mt-4 text-3xl font-bold tracking-tighter text-gray-800">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit
        </h3>
        <p class="mt-4 text-zinc-500">
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
        </p>
        <button class="mt-8 px-12 py-4 bg-blue-600 text-white text-lg hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500" tabindex="0">
          Read More >
        </button>
      </article>
      <!-- Side Posts -->
        <div class="col-span-2 flex flex-col gap-4 ">
          <article class="hover:bg-yellow-50 transition duration-150 ease-in-out bg-white p-6  ">
            <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
                By <span class="text-amber-300">John Doe</span> | May 23, 2022
              </time>
            <h3 class="mt-2 text-2xl font-bold text-gray-800">
              8 Figma design systems that you can download for free today
            </h3>
          </article>
          <article class="hover:bg-yellow-50 transition duration-150 bg-white p-6">
          <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
              By <span class="text-amber-300">John Doe</span> | May 23, 2022
            </time>
          <h3 class="hover:bg-yellow-50 transition duration-150 mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
         <article class="hover:bg-yellow-50 transition duration-150 bg-white p-6">
         <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
              By <span class="text-amber-300">John Doe</span> | May 23, 2022
            </time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
         <article class="hover:bg-yellow-50 transition duration-150 bg-white p-6">
         <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
              By <span class="text-amber-300">John Doe</span> | May 23, 2022
            </time>
          <h3 class="mt-2 text-2xl font-bold text-gray-800">
            8 Figma design systems that you can download for free today
          </h3>
        </article>
      </div>
    </div>

  </section>

  <!-- About Us Section -->
<section class="relative flex bg-purple-50 px-10 py-16 w-[87%] ml-[6%] shadow-md  mt-12 top-[100px]">
  <!-- Garis biru dan kuning di atas -->
  <div class="absolute top-[-22px] left-[25%] w-3/4 h-6 flex">
    <div class="bg-yellow-400 h-full w-3/4"></div>
    <div class="bg-blue-500 h-full w-1/4"></div>
  </div>

  <!-- Konten About Us dan Our Mission -->
  <div class="grid grid-cols-2 gap-10 w-full max-md:grid-cols-1 mt-8">
    <!-- About Us Section -->
    <div class="w-full px-6">
      <span class="uppercase tracking-[3px] font-semibold text-gray-800">ABOUT US</span>
      <h2 class="mt-4 text-[28px] md:text-[36px] font-bold tracking-tighter text-gray-800 leading-tight">
        We are a community of content writers who share their learnings
      </h2>
      <p class="mt-4 text-gray-600">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
      </p>
      <a href="#" class="mt-6 inline-block text-lg text-amber-400 hover:underline">Read More ></a>
    </div>

    <!-- Our Mission Section -->
    <div class="w-full px-6">
      <span class="uppercase tracking-[3px] font-semibold text-gray-800">OUR MISSION</span>
      <h3 class="mt-4 text-[28px] md:text-[30px] font-bold tracking-tighter text-gray-800 leading-tight">
        Creating valuable content for creatives all around the world
      </h3>
      <p class="mt-4 text-gray-600">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
      </p>
    </div>
  </div>
</section>


  <!-- Category Section -->
  <section class="px-20 py-12 max-md:px-8 translate-y-[30%] ">
    <h2 class="text-4xl font-bold tracking-tighter text-center text-gray-800 mb-12 ">
      Choose A Category
    </h2>
    <div class="grid grid-cols-4 gap-5 max-md:grid-cols-1">
      <!-- Category Cards -->
      <article class="border border-zinc-500 p-8 hover:bg-x-blue transition duration-150 ease-in-out">
        <RouterLink to="/category">
        <img loading="lazy" src="@/assets/images/logo/business.png"
          alt="Business category icon" class="w-10 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800">Business</h3>
        <p class="mt-1 text-zinc-500">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
        </RouterLink>
      </article>
      <!-- Repeat for other categories as needed -->
        <article class="border border-zinc-500 p-8 hover:bg-x-blue transition duration-150 ease-in-out">
          <RouterLink to="/category">
        <img loading="lazy" src="@/assets/images/logo/startup.png"
          alt="Business category icon" class="w-5 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800">StartUp</h3>
        <p class="mt-1 text-zinc-500">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
        </RouterLink>
      </article>
       <article class="border border-zinc-500 p-8 hover:bg-x-blue transition duration-150 ease-in-out">
        <RouterLink to="/category">
        <img loading="lazy" src="@/assets/images/logo/ekonomi.png"
          alt="Business category icon" class="w-10 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800">Economy</h3>
        <p class="mt-1 text-zinc-500">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
        </RouterLink>
      </article>
       <article class="border border-zinc-500 p-8 hover:bg-x-blue transition duration-150 ease-in-out">
        <RouterLink to="/category">
        <img loading="lazy" src="@/assets/images/logo/teknologi.png" 
          alt="Business category icon" class="w-10 aspect-square" />
        <h3 class="mt-4 text-3xl font-bold text-gray-800">Technology</h3>
        <p class="mt-1 text-zinc-500">
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        </p>
        </RouterLink>
      </article>
    </div>
  </section>

 <!-- Why We Started Section -->
<section class="relative flex justify-center max-w-screen mt-32 max-md:px-5 max-md:mt-10 translate-y-[10%]">
  <div class="flex flex-wrap justify-between items-center w-full max-w-5xl gap-10 translate-x-[-5%]">
    <img
      src="@/assets/images/misc/home/story.png"
      alt="Group image"
      class="w-full mt-10 px-2 max-w-4xl object-cover -z-10"/>

    <!-- Aside Section -->
    <aside class="absolute right-0 bottom-0 translate-y-0 bg-white p-10 py-10 px-30 w-[60%] translate-x-[20%] "> <!-- Menempatkan aside secara absolut -->
      <article>
        <span class="text-xs font-semibold uppercase tracking-wide text-gray-500">
          Why we started
        </span>
        <h2 class="mt-4 text-4xl font-bold text-gray-900">
          It started out as a simple idea and evolved into our passion
        </h2>
        <p class="mt-4  text-gray-600 leading-relaxed">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip.
        </p>
        <button class="mt-6 px-6 py-3 text-white bg-blue-600  hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500">
          Discover our story >
        </button>
      </article>
    </aside>
  </div>
</section>
 
 <!-- List of Authors Section -->
  <section class="px-20 py-24 text-center max-md:px-5 translate-y-[15%]">
    <h3 class="text-3xl font-bold text-gray-900">List of Authors</h3>
    <div class="grid grid-cols-4 gap-8 mt-12 max-md:grid-cols-1">
      <Router-Link to="/authors/author1">
      <div class="p-8 bg-gray-100 rounded-lg shadow">
        <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/floyd.png" alt="Floyd Miles" />
        <h4 class="mt-4 text-xl font-semibold text-gray-900">Floyd Miles</h4>
        <p class="text-sm text-gray-500">Content Writer @Company</p>
        <div class="flex justify-center mt-4 space-x-4 text-gray-500">
          <img src="@/assets/images/logo/socmedh.png">
        </div>
      </div>
      </Router-Link>
      <div class="p-8 bg-gray-100 rounded-lg shadow">
        <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/dianne.png" alt="Dianne Russell" />
        <h4 class="mt-4 text-xl font-semibold text-gray-900">Dianne Russell</h4>
        <p class="text-sm text-gray-500">Content Writer @Company</p>
        <div class="flex justify-center mt-4 space-x-4 text-gray-500">
          <img src="@/assets/images/logo/socmedh.png">
        </div>
      </div>
      <div class="p-8 bg-gray-100 rounded-lg shadow">
        <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/jenny.png" alt="Jenny Wilson" />
        <h4 class="mt-4 text-xl font-semibold text-gray-900">Jenny Wilson</h4>
        <p class="text-sm text-gray-500">Content Writer @Company</p>
        <div class="flex justify-center mt-4 space-x-4 text-gray-500">
          <img src="@/assets/images/logo/socmedh.png">
        </div>
      </div>
      <div class="p-8 bg-gray-100 rounded-lg shadow">
        <img class="w-20 h-20 mx-auto rounded-full" src="@/assets/images/misc/home/leslie.png" alt="Leslie Alexander" />
        <h4 class="mt-4 text-xl font-semibold text-gray-900">Leslie Alexander</h4>
        <p class="text-sm text-gray-500">Content Writer @Company</p>
        <div class="flex justify-center mt-4 space-x-4 text-gray-500">
          <img src="@/assets/images/logo/socmedh.png">
        </div>
      </div>
    </div>
    <img src="@/assets/images/logo/logo-ipsum.png" alt="logo ipsum" class="mt-[10%]">
  </section>

  <!--testimonials-->
   <section data-layername="testimonials" class="flex flex-col rounded-none translate-y-[15%]">
  <div data-layername="background" class="flex flex-col justify-center items-center px-16 py-20 w-[90%] ml-[5%] bg-orange-50 max-md:px-5 max-md:max-w-full">
    <!-- Pastikan grid-cols-1 pada breakpoint kecil -->
    <div class="grid grid-cols-2 gap-4  w-full max-w-[1057px] max-md:grid-cols-1 relative">
      <article class="flex flex-col items-start self-start mt-3 text-base text-gray-800 pr-5">
        <h2 data-layername="testimoniaLs" class="font-semibold leading-none uppercase tracking-[3px]">
          TESTIMONIALS
        </h2>
        <h3 data-layername="whatPeopleSayAboutOurBlog" class="mt-2 text-4xl font-bold tracking-tighter leading-10">
          What people say about our blog
        </h3>
        <p data-layername="loremIpsumDolorSitAmetConsecteturAdipiscingElitSedDoEiusmodTempor" class="self-stretch mt-4 leading-7">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.
        </p>
      </article>

      <!-- Garis Pemisah Tengah -->
  

      <article class="flex flex-col max-md:max-w-full pl-0 ">
        <blockquote class="self-start text-2xl font-bold leading-8 text-gray-800 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
        </blockquote>
        <footer class="flex flex-wrap gap-5 justify-between items-start mt-28 w-full max-md:mt-10 max-md:max-w-full">
          <div class="flex gap-4 mt-2">
            <img loading="lazy" src="@/assets/images/logo/pp.png" />
            <div class="flex flex-col">
              <cite class="text-2xl font-bold leading-none text-gray-800 not-italic">
                Jonathan Vallem
              </cite>
              <p class="self-start text-base leading-7 text-zinc-500">
                New York, USA
              </p>
            </div>
          </div>

          <!-- Navigation Buttons -->
          <div class="flex justify-end space-x-4 mt-8">
            <button class="w-10 h-10 rounded-full bg-white shadow hover:bg-gray-200 transition duration-200 flex items-center justify-center">
              <span class="text-gray-700 text-lg">&larr;</span>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-900 hover:bg-gray-800 text-white transition duration-200 flex items-center justify-center">
              <span class="text-lg">&rarr;</span>
            </button>
          </div>
        </footer>
      </article>
    </div>
  </div>
</section>


</template>


<style>
.vertical-line {
  width: 2px;                  /* Ketebalan garis */
  height: 200px;               /* Tinggi garis */
  background-color: #333;      /* Warna garis */
  margin: 0 10px;              /* Jarak dari elemen lain */
}

</style>
