<script setup>

</script>

<template>
  <footer class="bg-x-black px-20 py-14 mt-32 text-white max-md:px-5 max-md:mt-10">
    <div class="flex justify-between items-center mb-14">
      <img 
        loading="lazy" 
        src=" @/assets/images/logo/logo-finsweet.png"
        alt="Footer logo" 
        class="w-[140px]" 
      />
      <nav class="flex gap-6">
        <a href="/" class="text-white hover:text-x-yellow transition duration-150 ease-in-out">Home</a>
        <a href="/blog" class="text-white hover:text-x-yellow transition duration-150 ease-in-out">Blog</a>
        <a href="/about" class="text-white hover:text-x-yellow transition duration-150 ease-in-out">About us</a>
        <a href="/contact" class="text-white hover:text-x-yellow transition duration-150 ease-in-out">Contact us</a>
        <a href="/privacy" class="text-white hover:text-x-yellow transition duration-150 ease-in-out">Privacy Policy</a>
      </nav>
    </div>

   <div class="bg-white bg-opacity-10 px-14 py-20 max-md:px-5">
  <div class="flex items-center gap-5 max-md:flex-col">
    <!-- H2 Text -->
    <h2 class="text-3xl font-bold tracking-tighter w-6/12 max-md:w-full">
      Subscribe to our newsletter to get latest updates and news
    </h2>
    
    <!-- Form Section -->
    <div class="flex w-6/12  max-md:w-full">
      <form @submit.prevent="handleSubmit" class="flex gap-4 w-full max-md:flex-col max-md:gap-3">
        <label for="email" class="sr-only">Enter Your Email</label>
        <input 
          type="email" 
          id="email" 
          v-model="email"
          required
          placeholder="Enter Your Email"
          class="grow px-6 py-2 text-base border border-neutral-600 text-gray-800 bg-transparent focus:outline-none focus:ring-2 focus:ring-blue-300"
        />
        <button 
          type="submit"
          class="px-8 py-4 text-lg font-bold text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-300"
        >
          Subscribe
        </button>
      </form>
    </div>
  </div>
</div>

   

    <div class="mt-12 flex justify-between items-center text-white opacity-70">
      <address class="not-italic">
        Finstreet 118 2561 Fintown<br />
        Hello@finsweet.com 020 7993 2905
      </address>
      <img 
        loading="lazy" 
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/59f3f7554500ecc8432949d0d6c5048d89508b7fbdb85094720954ac88e22062?placeholderIfAbsent=true&apiKey=980ce9ece45c40d686dd0f20882b69da" 
        alt="Social media links" 
        class="w-36" 
      />
    </div>
  </footer>
</template>
