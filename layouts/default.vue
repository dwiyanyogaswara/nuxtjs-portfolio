<template>
  <div class="bg-gradient-to-r from-blue-500 to-blue-800 text-white">
    <div class="fixed top-0 left-0 right-0 z-10">
      <header class="shadow-2xl bg-gradient-to-r from-gray-700 to-black">
        <nav class="container p-5 mx-auto flex justify-between">
          <NuxtLink to="#home" class="text-white text-2xl tracking-widest">Dwiyan Yogaswara</NuxtLink>
          <ul class="flex gap-5 font-medium  tracking-widest">
            <li><NuxtLink to="#home" class="hover:font-bold hover:text-lg">Home</NuxtLink></li>
            <li><NuxtLink to="#skills" class="hover:font-bold hover:text-lg">Skills</NuxtLink></li>
            <li><NuxtLink to="#work" class="hover:font-bold hover:text-lg">Work Experience</NuxtLink></li>
            <!-- <li><NuxtLink to="#portfolio" class="hover:font-bold hover:text-l">Portfolio</NuxtLink></li> -->
          </ul>
        </nav>
      </header>
    </div>

    <div class="relative top-20"><slot /></div>
  </div>
</template>

<style scoped>
</style>