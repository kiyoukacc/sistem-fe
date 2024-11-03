<script>
export default {
  name: 'ImageComponent'
}
</script>

<template>
<!--article atas-->
<article class="flex flex-col items-start font-bold text-gray-800 max-w-[666px] mx-auto mt-12 mb-12">
    <header class="flex flex-col items-start gap-2">
      <div class="flex items-center gap-4 text-amber-300 text-3xl tracking-tighter leading-none w-full">
        <img 
          loading="lazy" 
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/aae13d551698e655ba062dfb4b62e3ed2b20b0d223c542e58ac3eaecec07eb05?placeholderIfAbsent=true&apiKey=99e98c75e74449b086557677558acabb" 
          alt="Profile picture of Andrew Jonson" 
          class="object-contain w-12 h-12 rounded-full"
        />
        <div class="flex flex-col items-start leading-tight">
          <h1 class="opacity-[0.87]">Andrew Jonson</h1>
          <p class="text-sm text-gray-500 font-normal">Posted on 27th January 2022</p>
        </div>
      </div>
    </header>
    
    <h2 class="self-start mt-9 text-5xl tracking-tighter leading-[64px] max-md:max-w-full max-md:text-4xl max-md:leading-[60px]">
        Step-by-step guide to choosing great font pairs
    </h2>

    <section class="flex items-center gap-2 mt-4 text-2xl text-gray-600 whitespace-nowrap">
      <img 
        loading="lazy" 
        src="https://cdn.builder.io/api/v1/image/assets/TEMP/368cc451f8ea7eaa6a1734c70d003b683a7926e64d4258413053a719f4a187c2?placeholderIfAbsent=true&apiKey=99e98c75e74449b086557677558acabb" 
        alt="Startup category icon" 
        class="object-contain w-6 h-6"
      />
      <p class="text-2xl">Startup</p>
    </section>
  </article>

  <!--image tengah-->
   <section class="image-container mt-12 px-4 mb-12">
    <img 
      loading="lazy" 
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/ed86b5f338df63527d72f7570e20f6aa1b2e2dac87bb4611ea9cc3579eb115b6?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" 
      alt="" 
      class="object-contain w-full max-w-[90%] mx-auto aspect-[2.2]" 
      role="presentation"
    />
  </section>

  <!--text tengah-->
  <section class="flex justify-center mt-12">
    <article class="flex flex-col items-start text-base leading-7 max-w-[822px] text-zinc-500">
      <header>
        <h1 class="z-10 mt-0 mr-0 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
        </h1>
      </header>

      <section>
        <p class="mt-4 mr-0 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
        </p>
      </section>

      <section>
        <h2 class="mt-12 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:mt-10 max-md:-mr-3.5 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
        </h2>
        <p class="mt-4 max-md:mr-0 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
        </p>
        <p class="mt-6 mr-0 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
        </p>
      </section>

      <aside class="flex flex-col items-start mt-6 ml-4 text-2xl font-bold leading-none text-gray-900 max-md:max-w-full">
        <h3 class="bullet-item">Lorem ipsum dolor sit amet</h3>
        <h3 class="bullet-item">Non blandit massa enim nec scelerisque</h3>
        <h3 class="bullet-item">Neque egestas congue quisque egestas</h3>
      </aside>

      <section>
        <p class="mt-6 max-md:-mr-3.5 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
        </p>
      </section>

      <section>
        <h2 class="mt-12 mr-0 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:mt-10 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod.
        </h2>
        <p class="z-10 mt-4 max-md:mr-0 max-md:max-w-full">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus. Sociis natoque penatibus et magnis dis parturient montes. Ridiculus mus mauris vitae ultricies leo. Neque egestas congue quisque egestas diam. Risus in hendrerit gravida rutrum quisque non.
        </p>
      </section>
    </article>
  </section>
  
<!--article bawah-->
  <section class="flex flex-col mt-12 px-4">
    <div class="max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2">
          <div class="flex flex-col grow items-start font-bold text-gray-800 max-md:mt-8">
            <h2 data-layername="whatToReadNext" class="text-4xl tracking-tighter leading-none text-center text-black">
              What to read next
            </h2>
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/489ef74091731b961fbf3969c34e7f36951426f47bd22fe7c27380087b8d8e37?placeholderIfAbsent=true&apiKey=99e98c75e74449b086557677558acabb" alt="Featured blog post image" class="object-contain self-stretch mt-16 w-full aspect-[1.27] max-md:mt-10" />
            <time datetime="2021-08-23" class="mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
            </time>
            <h3 class="mt-4 text-3xl tracking-tighter leading-10">
              A UX Case Study Creating a Studious Environment for Students:
            </h3>
            <p class="self-stretch mt-4 text-base leading-7 opacity-70">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2">
          <div class="flex flex-col grow mt-28 text-gray-800 max-md:mt-10">
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/c071cc6ee949150dc47808b7c7d4f8389bbb0d68410e5c84462417223aa0ec56?placeholderIfAbsent=true&apiKey=99e98c75e74449b086557677558acabb" alt="Featured blog post image" class="object-contain w-full aspect-[1.27]" />
            <time datetime="2021-08-23" class="self-start mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
            </time>
            <h3 class="self-start mt-4 text-3xl font-bold tracking-tighter leading-10">
              A UX Case Study Creating a Studious Environment for Students:
            </h3>
            <p class="mt-4 text-base leading-7 opacity-70">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>

        <article class="flex flex-col w-[33%] max-md:ml-0 max-md:w-full mx-2">
          <div class="flex flex-col grow mt-28 text-gray-800 max-md:mt-10">
            <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/e813ed92f073a9f0fedfb64474213d579e09a3e65fb95a3cf5e92cd7f6c18250?placeholderIfAbsent=true&apiKey=99e98c75e74449b086557677558acabb" alt="Featured blog post image" class="object-contain w-full aspect-[1.27]" />
            <time datetime="2021-08-23" class="self-start mt-8 text-sm font-medium leading-none text-amber-300">
              By <span class="text-amber-300">John Doe</span> l Aug 23, 2021
            </time>
            <h3 class="self-start mt-4 text-3xl font-bold tracking-tighter leading-10">
              A UX Case Study Creating a Studious Environment for Students:
            </h3>
            <p class="mt-4 text-base leading-7 opacity-70">
              Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
            </p>
          </div>
        </article>
      </div>
    </div> 
  </section>
</template>

<style scoped>
.builder-component {
  max-width: none !important;
}

</style>