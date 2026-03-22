<template>
  <footer class="border-t border-border-color/50 bg-background-light dark:bg-background-dark py-12">
    <div
      class="mx-auto max-w-7xl px-6 flex flex-col md:flex-row justify-between items-center gap-6"
    >
      <Logo />

      <div class="flex gap-8 text-sm text-text-muted dark:text-gray-400">
        <NuxtLink class="hover:text-primary transition-colors" to="/">Privacy Policy</NuxtLink>
        <NuxtLink class="hover:text-primary transition-colors" to="/">Terms of Trade</NuxtLink>
        <NuxtLink class="hover:text-primary transition-colors" to="/">JP Business Reg</NuxtLink>
      </div>
      <div class="text-sm text-text-muted dark:text-gray-500">
        © 2023 Trusffle Australia. All rights reserved.
      </div>
    </div>
  </footer>
</template>
