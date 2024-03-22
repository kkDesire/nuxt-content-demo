<template>
  <div class="max-w-3xl px-4 mx-auto">
    <!-- Begin ::: Header ::: -->
    <header class="mt-8 mb-4 flex justify-between items-end">
      <div>
        <h1 class="text-2xl font-semibold">
          <NuxtLink to="/">Personnal Blog</NuxtLink>
        </h1>
        <p class="text-gray-500">Learn programming easly</p>
      </div>
      <Btn>Hire Me</Btn>
    </header>
    <!-- End   ::: Header ::: -->

    <!-- Begin ::: Main Content ::: -->
    <NuxtPage />
    <!-- End   ::: Main Content ::: -->
  </div>
</template>
<style>
body {
  @apply bg-gray-100;
}
</style>
