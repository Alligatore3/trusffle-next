<template>
  <!-- HeroSection -->
  <div class="relative flex w-full flex-col items-center justify-center">
    <div class="w-full max-w-[1200px] px-4 py-8 md:py-16">
      <div
        class="relative overflow-hidden rounded-xl md:rounded-[3rem] aspect-[4/3] md:aspect-[21/9] bg-cover bg-center group"
        data-alt="Close up of hands holding a fresh black truffle with soil, soft morning sunlight"
        style="
          background-image:
            linear-gradient(rgba(0, 0, 0, 0.2), rgba(0, 0, 0, 0.5)),
            url('https://lh3.googleusercontent.com/aida-public/AB6AXuCJdMPIElh1g6gFa4dag2C4jPlZ8Lkr-LM_n6dxPCkLsGXLYb3MetdP4lt9o0ukuAImeKXrTrTd052r0khE6JYnajpgnoK8rHiaCM42MiK6QAW6BQfBT3lXQjRDEj2pqcjyXXkity9xx4HsPmCCl1ABi3QYj4EiMduXbiabx0NReSr5rkMzWW1bomaV45BLzV0CXeszr4jziauHM34R7-jJvQ2L7RQHsC6_zXMlNNN9LukIyeLCplo56swWjoDcFuzobcuJqXjgDkmw');
        "
      >
        <div
          class="absolute inset-0 flex flex-col items-center justify-center text-center p-6 md:p-12"
        >
          <span
            class="mb-4 inline-block rounded-full bg-white/20 px-4 py-1.5 text-xs font-bold uppercase tracking-widest text-white backdrop-blur-sm"
          >
            Since 2018
          </span>
          <h1
            class="text-white text-4xl md:text-6xl font-black leading-tight tracking-[-0.033em] max-w-3xl drop-shadow-sm"
          >
            Cultivating Trust under the Australian Sun
          </h1>
          <p class="mt-6 text-white/90 text-base md:text-xl font-normal max-w-2xl leading-relaxed">
            Bridging Australian soil and Japanese dining tables with premium craftsmanship and
            uncompromising standards.
          </p>
          <div class="mt-10">
            <button
              class="flex items-center gap-2 rounded-full bg-primary px-8 py-3 text-sm font-bold text-black transition-transform hover:scale-105"
            >
              <span>Read Our Philosophy</span>
              <span class="material-symbols-outlined text-sm">arrow_downward</span>
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Origin Section (Modified HeroSection layout) -->
  <div class="w-full flex justify-center py-12 md:py-24 bg-white dark:bg-[#1a190b]">
    <div class="max-w-[1200px] w-full px-6 flex flex-col md:flex-row gap-12 items-center">
      <div class="w-full md:w-1/2 flex flex-col gap-6">
        <span class="text-primary font-bold tracking-widest uppercase text-sm">Our Origin</span>
        <h2
          class="text-4xl md:text-5xl font-black tracking-tight text-[#1c1c0d] dark:text-white leading-tight"
        >
          Where the Earth <br />Meets Excellence
        </h2>
        <div class="w-20 h-1 bg-primary rounded-full"></div>
        <p class="text-lg text-gray-600 dark:text-gray-300 leading-relaxed">
          Founded on the principles of respect for nature and uncompromising quality, our farm is
          located in the pristine heart of Australia's truffle country. Here, the unique climate
          creates the perfect conditions for the Black Perigord Truffle.
        </p>
        <p class="text-lg text-gray-600 dark:text-gray-300 leading-relaxed">
          We understand that for the Japanese palate, freshness is paramount. By leveraging the
          counter-seasons, we bring the depth of winter truffles to Japan's summer dining tables.
        </p>
        <div class="pt-4">
          <div class="flex items-center gap-4">
            <div class="flex -space-x-4">
              <img
                class="w-12 h-12 rounded-full border-2 border-white dark:border-[#23220f] object-cover"
                data-alt="Portrait of a truffle farmer smiling"
                src="https://lh3.googleusercontent.com/aida-public/AB6AXuBWIxDfAiNE0vl9-6KI4hnSVwVC4iHLZhbwssoYK-ygReciqN6VhTUpjtlGXa0zDnJU6iRSPuazTCXk3xuKGQEh_bR2DdC1aoFdyqS28Q1KWkdrKeIFrrry2Z7YgLRZnWBqFhLIf1r9G6ZgM96n-abSP6QaEXPkPa19Uv_YOoszQzaNjpuh_Yjn6xkRntlcx7RTiEdwLuTJTChqYmVQ2YHQ4dORYDUZJ2K0437KwvHFYxsH-upwC2VD5Hk6WWabqWv-QUBealvOhGCY"
              />
              <img
                class="w-12 h-12 rounded-full border-2 border-white dark:border-[#23220f] object-cover"
                data-alt="Portrait of a truffle dog"
                src="https://lh3.googleusercontent.com/aida-public/AB6AXuC6-1mqMzxUulFrTBt79izrlub-JyeW1jlHChhhe7ugKCAwYQH4c19CkSTWVQzzvYfkato5mR8jtdXmN_XFW2sioUDS-gN0Jo3VOXM_LQJL3U0xDl0lt60aJCftr8ZaWAVF8MbdLnKnfwyvQww7lWaVxTDBCzBs_omZVH-hnoXkbs3DqL4GilPJiDKZREw5ng2wdUZpnXggIoJejxkPyev1uo3YH3hkQVtb9EaJu1CCHSbvyD2bAP5QdGrhDM5LiIiSbBQbfH6S8Em-"
              />
            </div>
            <div class="flex flex-col">
              <span class="text-sm font-bold text-[#1c1c0d] dark:text-white">James & 'Mochi'</span>
              <span class="text-xs text-gray-500">Head Grower & Chief Sniffer</span>
            </div>
          </div>
        </div>
      </div>
      <div class="w-full md:w-1/2 relative">
        <div class="absolute -top-10 -right-10 w-32 h-32 bg-primary/20 rounded-full blur-3xl"></div>
        <div
          class="absolute -bottom-10 -left-10 w-40 h-40 bg-primary/20 rounded-full blur-3xl"
        ></div>
        <div
          class="relative w-full aspect-square md:aspect-[4/5] bg-cover bg-center rounded-[3rem] shadow-xl overflow-hidden"
          data-alt="Morning mist over rows of oak trees in a truffle orchard"
          style="
            background-image: url('https://lh3.googleusercontent.com/aida-public/AB6AXuB4wI5yVypoTbwLMsSmHZoLhN_KHyRadam7glQN5og9TMSOEMn8ZtF1YE_3DQ8yWbxj_jJD5TDDhLzL37zry42xdPVZo5e3eWdB9g30YOF4AUNezDVoFqxldH-6FTqySb1pUiDrvXXOZuG-dLxEsLDQa34U5vIqzzNywX6tOb5DMKXXwaPBqU6i-lPnKf74aWQ-kzBeQpCEYJhv7WdIBLkUfyF00hBLrGLth3MAUHq0GroJ-KRxoTNMupqY5efP-j_7iOtR7fMetN8S');
          "
        ></div>
      </div>
    </div>
  </div>
  <!-- FeatureSection (The Trusffle Standard) -->
  <div class="w-full flex justify-center py-16 bg-background-light dark:bg-background-dark">
    <div class="max-w-[1200px] w-full px-6 flex flex-col gap-16">
      <div class="flex flex-col gap-4 text-center items-center">
        <span
          class="px-3 py-1 rounded-full border border-gray-200 dark:border-gray-700 text-xs font-semibold uppercase tracking-wider text-gray-500 dark:text-gray-400"
          >Our Philosophy</span
        >
        <h2
          class="text-3xl md:text-5xl font-black tracking-tight text-[#1c1c0d] dark:text-white max-w-2xl"
        >
          The Trusffle Standard
        </h2>
        <p class="text-gray-600 dark:text-gray-300 text-base md:text-lg max-w-2xl">
          Our philosophy is built on four pillars of excellence, ensuring every truffle meets the
          highest expectations of our chefs and partners.
        </p>
      </div>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-6">
        <!-- Card 1 -->
        <div
          class="group flex flex-col gap-4 rounded-2xl bg-white dark:bg-[#1a190b] p-6 shadow-sm hover:shadow-md transition-all border border-transparent hover:border-primary/30"
        >
          <div
            class="size-12 rounded-full bg-primary/20 flex items-center justify-center text-[#1c1c0d] dark:text-white group-hover:bg-primary transition-colors"
          >
            <span class="material-symbols-outlined">handshake</span>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-lg font-bold">Trust</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 leading-relaxed">
              Complete transparency in every step of the journey. We are partners, not just
              suppliers.
            </p>
          </div>
        </div>
        <!-- Card 2 -->
        <div
          class="group flex flex-col gap-4 rounded-2xl bg-white dark:bg-[#1a190b] p-6 shadow-sm hover:shadow-md transition-all border border-transparent hover:border-primary/30"
        >
          <div
            class="size-12 rounded-full bg-primary/20 flex items-center justify-center text-[#1c1c0d] dark:text-white group-hover:bg-primary transition-colors"
          >
            <span class="material-symbols-outlined">psychology</span>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-lg font-bold">Craftsmanship</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 leading-relaxed">
              Hand-harvested with trained dogs. We touch the earth lightly and respect the yield.
            </p>
          </div>
        </div>
        <!-- Card 3 -->
        <div
          class="group flex flex-col gap-4 rounded-2xl bg-white dark:bg-[#1a190b] p-6 shadow-sm hover:shadow-md transition-all border border-transparent hover:border-primary/30"
        >
          <div
            class="size-12 rounded-full bg-primary/20 flex items-center justify-center text-[#1c1c0d] dark:text-white group-hover:bg-primary transition-colors"
          >
            <span class="material-symbols-outlined">verified_user</span>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-lg font-bold">Food Safety</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 leading-relaxed">
              Rigorous cleaning and inspection that exceeds international export standards.
            </p>
          </div>
        </div>
        <!-- Card 4 -->
        <div
          class="group flex flex-col gap-4 rounded-2xl bg-white dark:bg-[#1a190b] p-6 shadow-sm hover:shadow-md transition-all border border-transparent hover:border-primary/30"
        >
          <div
            class="size-12 rounded-full bg-primary/20 flex items-center justify-center text-[#1c1c0d] dark:text-white group-hover:bg-primary transition-colors"
          >
            <span class="material-symbols-outlined">wb_sunny</span>
          </div>
          <div class="flex flex-col gap-2">
            <h3 class="text-lg font-bold">Seasonality</h3>
            <p class="text-sm text-gray-500 dark:text-gray-400 leading-relaxed">
              Bringing the richness of the Southern Hemisphere winter to the Japanese summer.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- Quote Block -->
  <div class="w-full flex justify-center py-20 bg-[#f4f4e6] dark:bg-[#1f1e10]">
    <div class="max-w-[800px] w-full px-6 text-center relative">
      <span
        class="material-symbols-outlined absolute top-0 left-0 text-6xl text-primary/40 -translate-x-1/2 -translate-y-1/2 hidden md:block"
        >format_quote</span
      >
      <blockquote
        class="text-2xl md:text-3xl font-medium italic text-[#1c1c0d] dark:text-white leading-normal"
      >
        "We don't just grow truffles; we cultivate an experience. For our Japanese friends, it is
        about honoring the ingredient by delivering it in its purest, most perfect form."
      </blockquote>
      <div class="mt-8 flex flex-col items-center">
        <div class="w-16 h-1 bg-primary mb-4 rounded-full"></div>
        <cite class="not-italic font-bold text-lg">James Mitchell</cite>
        <span class="text-sm text-gray-500">Founder, Trusffle</span>
      </div>
    </div>
  </div>
  <!-- Timeline / Process Section -->
  <div
    class="w-full flex justify-center py-16 md:py-24 bg-background-light dark:bg-background-dark"
  >
    <div class="max-w-[1000px] w-full px-6">
      <div class="flex flex-col md:flex-row gap-12 items-start">
        <div class="md:w-1/3 sticky top-24">
          <h2 class="text-3xl font-black text-[#1c1c0d] dark:text-white mb-4">
            From Soil to Sushi Bar
          </h2>
          <p class="text-gray-600 dark:text-gray-300 mb-8">
            Our logistics are fine-tuned for speed. We understand that a truffle loses aroma every
            hour it is out of the ground. That's why we race the clock.
          </p>
          <button
            class="hidden md:flex min-w-[84px] cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-6 bg-[#f9f506] text-[#1c1c0d] text-base font-bold leading-normal tracking-[0.015em] hover:bg-yellow-400 transition-colors shadow-lg shadow-primary/20"
          >
            <span class="truncate">View Wholesale Options</span>
          </button>
        </div>
        <div class="md:w-2/3 w-full pl-0 md:pl-12">
          <!-- Timeline Item 1 -->
          <div class="flex gap-4 pb-12 relative group">
            <div
              class="absolute left-[19px] top-10 bottom-0 w-0.5 bg-gray-200 dark:bg-gray-700 group-last:hidden"
            ></div>
            <div class="flex flex-col items-center gap-2">
              <div
                class="w-10 h-10 rounded-full bg-white dark:bg-[#333] border-2 border-primary flex items-center justify-center shrink-0 z-10"
              >
                <span class="material-symbols-outlined text-primary text-sm">pets</span>
              </div>
            </div>
            <div class="flex flex-col pt-1">
              <span class="text-xs font-bold text-primary uppercase tracking-wide mb-1"
                >Early Morning (6:00 AM)</span
              >
              <h3 class="text-xl font-bold text-[#1c1c0d] dark:text-white mb-2">Harvesting</h3>
              <p class="text-gray-500 dark:text-gray-400 text-sm">
                Our dogs locate the ripe truffles. They are gently unearthed by hand to prevent any
                damage to the skin.
              </p>
            </div>
          </div>
          <!-- Timeline Item 2 -->
          <div class="flex gap-4 pb-12 relative group">
            <div
              class="absolute left-[19px] top-10 bottom-0 w-0.5 bg-gray-200 dark:bg-gray-700 group-last:hidden"
            ></div>
            <div class="flex flex-col items-center gap-2">
              <div
                class="w-10 h-10 rounded-full bg-white dark:bg-[#333] border-2 border-primary flex items-center justify-center shrink-0 z-10"
              >
                <span class="material-symbols-outlined text-primary text-sm">rule</span>
              </div>
            </div>
            <div class="flex flex-col pt-1">
              <span class="text-xs font-bold text-primary uppercase tracking-wide mb-1"
                >Mid-Morning (10:00 AM)</span
              >
              <h3 class="text-xl font-bold text-[#1c1c0d] dark:text-white mb-2">
                On-Site Selection
              </h3>
              <p class="text-gray-500 dark:text-gray-400 text-sm">
                Truffles are washed, dried, and graded immediately. Only the 'Extra Class' are
                selected for the Japanese market.
              </p>
            </div>
          </div>
          <!-- Timeline Item 3 -->
          <div class="flex gap-4 pb-12 relative group">
            <div
              class="absolute left-[19px] top-10 bottom-0 w-0.5 bg-gray-200 dark:bg-gray-700 group-last:hidden"
            ></div>
            <div class="flex flex-col items-center gap-2">
              <div
                class="w-10 h-10 rounded-full bg-white dark:bg-[#333] border-2 border-primary flex items-center justify-center shrink-0 z-10"
              >
                <span class="material-symbols-outlined text-primary text-sm">verified</span>
              </div>
            </div>
            <div class="flex flex-col pt-1">
              <span class="text-xs font-bold text-primary uppercase tracking-wide mb-1"
                >Afternoon (2:00 PM)</span
              >
              <h3 class="text-xl font-bold text-[#1c1c0d] dark:text-white mb-2">
                Safety Inspection
              </h3>
              <p class="text-gray-500 dark:text-gray-400 text-sm">
                A secondary rigorous inspection ensures no soil remains, meeting strict import
                regulations.
              </p>
            </div>
          </div>
          <!-- Timeline Item 4 -->
          <div class="flex gap-4 relative group">
            <div class="flex flex-col items-center gap-2">
              <div
                class="w-10 h-10 rounded-full bg-primary flex items-center justify-center shrink-0 z-10 shadow-lg shadow-primary/40"
              >
                <span class="material-symbols-outlined text-black text-sm">flight_takeoff</span>
              </div>
            </div>
            <div class="flex flex-col pt-1">
              <span class="text-xs font-bold text-primary uppercase tracking-wide mb-1"
                >Evening (Same Day)</span
              >
              <h3 class="text-xl font-bold text-[#1c1c0d] dark:text-white mb-2">Express Export</h3>
              <p class="text-gray-500 dark:text-gray-400 text-sm">
                Packed in chilled containers and dispatched to the airport. Arriving in Tokyo within
                24-48 hours of harvest.
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-8 md:hidden">
        <button
          class="w-full cursor-pointer items-center justify-center overflow-hidden rounded-full h-12 px-6 bg-[#f9f506] text-[#1c1c0d] text-base font-bold leading-normal tracking-[0.015em] hover:bg-yellow-400 transition-colors shadow-lg shadow-primary/20"
        >
          <span class="truncate">View Wholesale Options</span>
        </button>
      </div>
    </div>
  </div>
</template>
