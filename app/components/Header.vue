<template>
  <header
    class="sticky top-0 z-50 w-full border-b border-border-color/50 bg-background-light/95 backdrop-blur-md dark:bg-background-dark/95"
  >
    <div class="mx-auto flex h-20 max-w-7xl items-center justify-between px-6 lg:px-12">
      <div class="flex items-center gap-3 text-text-main dark:text-white">
        <span class="material-symbols-outlined text-3xl text-primary-content dark:text-primary"
          >diamond</span
        >
        <h2 class="text-xl font-bold tracking-tight">Trusffle</h2>
      </div>
      <nav class="hidden md:flex items-center gap-8">
        <a
          class="text-sm font-medium hover:text-primary-content/70 dark:text-gray-200 transition-colors"
          href="#story"
          >Our Story</a
        >
        <a
          class="text-sm font-medium hover:text-primary-content/70 dark:text-gray-200 transition-colors"
          href="#quality"
          >Quality</a
        >
        <a
          class="text-sm font-medium hover:text-primary-content/70 dark:text-gray-200 transition-colors"
          href="#seasonality"
          >Seasonality</a
        >
        <a
          class="text-sm font-medium hover:text-primary-content/70 dark:text-gray-200 transition-colors"
          href="#contact"
          >Contact</a
        >
      </nav>
      <button
        class="flex h-10 items-center justify-center rounded-full bg-primary px-6 text-sm font-bold text-primary-content transition-transform hover:scale-105 active:scale-95 shadow-lg shadow-primary/20"
      >
        <span class="truncate">Inquire</span>
      </button>
    </div>
  </header>
</template>
