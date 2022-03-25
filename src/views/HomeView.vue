<script setup>
  import Hero from '@/components/homepage/Hero.vue'
  import Categories from '@/components/homepage/Categories.vue'
</script>

<template>
  <main>
    <Hero />
    <Categories />

    <div class="container px-4 mx-auto my-16 md:px-12">
      <h2 class="mb-4 text-xl font-medium md:mb-0 md:text-lg">New Items</h2>
      <div class="flex flex-wrap -mx-1 lg:-mx-4">
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="#">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-1.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Mobile UI Kit
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Mobile UI Kit
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="#">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-2.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Online Doctor Consultation
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Website UI Kit
              </span>
            </header>
          </div>
        </div>
        <div class="w-full px-1 my-1 md:w-1/2 lg:my-4 lg:px-4 lg:w-1/3">
          <div class="overflow-hidden border border-gray-200 rounded-xl">
            <a href="#">
              <div class="m-4 overflow-hidden rounded-xl">
                <img
                  alt="Placeholder"
                  class="block w-full h-auto"
                  src="@/assets/img/items-3.jpg"
                />
              </div>
            </a>

            <header
              class="px-4 mb-4 leading-tight"
            >
              <h1 class="text-lg">
                <a class="font-semibold text-black no-underline hover:underline" href="#">
                  Banking Crypto
                </a>
              </h1>
              <span class="block text-sm font-light text-gray-500 no-underline">
                Mobile UI Kit
              </span>
            </header>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>
