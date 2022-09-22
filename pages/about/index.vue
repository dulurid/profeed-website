<script setup>
const projects = [
  "https://images.unsplash.com/photo-1467232004584-a241de8bcf5d?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=869&q=80",
  "https://images.unsplash.com/photo-1522204523234-8729aa6e3d5f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80",
  "https://images.unsplash.com/photo-1601506521937-0121a7fc2a6b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=871&q=80",
  "https://images.unsplash.com/photo-1633793566063-52465a148cc7?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80  ",
];
</script>

<template>
  <div class="flex flex-col gap-16">
    <div id="heros" class="p-4 mx-auto max-w-7xl">
      <div class="flex items-center gap-4">
        <div class="w-1/2">
          <div class="flex flex-col max-w-xl mx-auto item">
            <h1 class="text-5xl font-bold">Whats make us different</h1>
            <h3 class="mt-4 text-lg text-gray-600">
              A subheading that addresses the what, the why we should care and
              hopefully some social proof.
            </h3>

            <div class="flex gap-2 my-8">
              <button class="h-10 px-4 text-white bg-gray-900 rounded-full">
                Get Started
              </button>
            </div>
          </div>
        </div>

        <div class="w-1/2 bg-black h-[600px]">
          <img
            class="h-[600px] w-full object-cover"
            src="https://images.unsplash.com/photo-1592827086844-b20636fd80c9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80"
            alt=""
          />
        </div>
      </div>

      <section class="w-full py-8 bg-white sm:py-12 md:py-16">
        <div class="mx-auto max-w-7xl">
          <div class="grid grid-cols-8">
            <div
              v-for="value in projects"
              :key="value"
              class="relative col-span-12 lg:col-span-4"
            >
              <a href="#_" class="relative block w-full overflow-hidden h-72">
                <img
                  class="object-cover object-center w-full h-full transition duration-500 ease-out transform scale-100 item-center hover:scale-105"
                  :src="value"
                  alt=""
                />
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>
