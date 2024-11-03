

<template>
    <section class="p-20 w-full bg-purple-50 max-md:px-5 max-md:max-w-full ">
      <article class="flex gap-5 max-md:flex-col">
        <div class="flex flex-col w-[55%] max-md:ml-0 max-md:w-full">
          <div class="flex flex-col items-start self-stretch my-auto w-full font-medium max-md:mt-10 max-md:max-w-full">
            <span class="text-base leading-none text-gray-800 uppercase tracking-[3px]">Featured Post</span>
            <h1 class="self-stretch mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">
              Step-by-step guide to choosing great font pairs
            </h1>
            <time datetime="2022-05-23" class="mt-4 text-sm leading-none text-black">
              By <span class="text-amber-300">John Doe</span> | May 23, 2022
            </time>
            <p class="self-stretch mt-10 leading-6 text-zinc-500 ">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
            <router-link to="/blogpost">
              <button class="gap-3 px-8 py-3 mt-8 text-lg font-bold leading-none text-white bg-blue-600 max-md:px-5">
                Read More &gt;
              </button>
            </router-link>
          </div>
        </div>
        <div class="flex flex-col ml-5 w-[45%] max-md:ml-0 max-md:w-full translate-x-[6%]">
          <img loading="lazy" src="@/assets/images/misc/blog/blog1.png" />
        </div>
      </article>
    </section>

    <!-- Rest of the content follows the same pattern with semantic HTML elements -->
    <!-- Including the blog posts list, categories section, and newsletter subscription -->
    <!-- All Posts Section -->
    <section class="blog-cards mx-auto max-w-7xl px-8">
      <h2 class="text-4xl font-bold text-gray-900 mb-10 mt-10">All posts</h2>
      <hr data-layername="allBlogsDivider" class="mt-8 mb-10 w-full border border-zinc-300 opacity-22 max-md:max-w-full" aria-hidden="true">
      <div class="space-y-10 ">
        <article class="flex gap-6 items-start ">
          <img src="@/assets/images/misc/blog/blog2.png" alt="Post Image" class="flex flex-col ml-0 w-[35%] object-cover">
          <div class="w-[50%] mt-10  max-md:w-full">
            <span class="mt-10 text-lg font-semibold text-amber-400 uppercase">Startup</span>
            <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Design tips for designers that cover everything you need</h3>
            <p class="mt-4 leading-7 text-zinc-500">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <!-- Repeat the post structure for each post -->
        <article class="flex gap-6 items-start">
          <img src="@/assets/images/misc/blog/blog3.png" alt="Post Image" class="flex flex-col ml-0 w-[35%] object-cover ">
          <div class="w-[50%] mt-10 max-md:w-full">
            <span class="text-lg font-semibold text-amber-400 uppercase">Business</span>
            <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">How to build rapport with your web design clients</h3>
            <p class="mt-4 leading-7 text-zinc-500">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex gap-6 items-start">
          <img src="@/assets/images/misc/blog/blog4.png" alt="Post Image" class="flex flex-col ml-0 w-[35%] object-cover">
          <div class="w-[50%] mt-10 max-md:w-full">
            <span class="text-lg font-semibold text-amber-400 uppercase">Startup</span>
            <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Logo design trends to avoid in 2022</h3>
            <p class="mt-4 leading-7 text-zinc-500 ">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex gap-6 items-start">
          <img src="@/assets/images/misc/blog/blog5.png" alt="Post Image" class="flex flex-col ml-0 w-[35%] object-cover">
          <div class="w-[50%] mt-10 max-md:w-full">
            <span class="text-lg font-semibold text-amber-400 uppercase">Technology</span>
            <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">8 Figma design systems you can download for free today</h3>
            <p class="mt-4 leading-7 text-zinc-500">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex gap-6 items-start">
          <img src="@/assets/images/misc/blog/blog2.png" alt="Post Image" class="flex flex-col ml-0 w-[35%] object-cover ">
          <div class="w-[50%] mt-10 max-md:w-full">
            <span class="text-lg font-semibold text-amber-400 uppercase">Economy</span>
            <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Font sizes in UI design: The complete guide to follow</h3>
            <p class="mt-4 leading-7 text-zinc-500">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>
      </div>
      <!--pagination-->
      <div class="mt-[5%]">
      <nav aria-label="Pagination" data-layername="pagination" class="flex justify-center items-center gap-4 font-bold text-center p-2 mx-auto">
    <button 
      data-layername="prev" 
      class="flex items-center text-lg text-gray-500 hover:text-black transition-colors duration-200 focus:outline-none focus:ring-0"
      @click="goToPrevious"
    >
      &lt; <span class="ml-1">Prev</span>
    </button>
    <router-link
      to="/blogpost"
      class="flex items-center text-lg text-gray-500 hover:text-black transition-colors duration-200 focus:outline-none focus:ring-0"
    >
      <span class="mr-1">Next</span> &gt;
    </router-link>
  </nav>
  </div>
    </section>

   <!-- Category Section -->
  <section class="px-20 py-10 max-md:px-8 translate-y-[5%]">
    <h2 class="text-4xl font-bold tracking-tighter text-gray-800 mb-12 ">
      All Categories
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

</template>

<script>
import { RouterLink } from 'vue-router';

export default {
  name: 'CategoryView',
  methods: {
    goToPrevious() {
      // Tambahkan logika untuk mengarahkan ke halaman sebelumnya
      console.log('Going to previous page');
    }
  }
};
</script>
