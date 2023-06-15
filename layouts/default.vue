<template>
  <div class="bg-gradient-to-r from-blue-500 to-blue-900">
    <div class="fixed top-0 left-0 right-0 z-10">
      <header class="shadow-2xl bg-blue-950">
        <nav class="container p-5 mx-auto flex justify-between">
          <NuxtLink to="#home" class="text-white text-2xl">Dwiyan Yogaswara</NuxtLink>
          <ul class="flex gap-5 text-white font-medium">
            <li><NuxtLink to="#home" class="hover:font-bold hover:text-l">Home</NuxtLink></li>
            <li><NuxtLink to="#work" class="hover:font-bold hover:text-l">Work Experience</NuxtLink></li>
            <li><NuxtLink to="#portfolio" class="hover:font-bold hover:text-l">Portfolio</NuxtLink></li>
            <li><NuxtLink to="#skills" class="hover:font-bold hover:text-l">Skills</NuxtLink></li>
            <li><NuxtLink to="#education" class="hover:font-bold hover:text-l">Education</NuxtLink></li>
          </ul>
        </nav>
      </header>
    </div>

    <div class="relative top-20"><slot /></div>
  </div>
</template>

<style scoped>
</style>