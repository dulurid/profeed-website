<script setup>
useHead({
  title: "Profeed",
  viewport: "width=device-width, initial-scale=1, maximum-scale=1",
  charset: "utf-8",
  meta: [{ name: "description", content: "My amazing site." }],
  bodyAttrs: {
    class: "test",
  },
});

const slideUp = (delay) => {
  return {
    initial: {
      y: 100,
      opacity: 0,
    },
    visibleOnce: {
      y: 0,
      opacity: 1,
      transition: {
        type: "spring",
        stiffness: 350,
        damping: 20,
        delay: delay,
      },
    },
  };
};
</script>

<template>
  <div>
    <div id="heros" class="max-w-7xl mx-auto p-4 pt-16">
      <div
        class="flex flex-col items-center justify-center max-w-xl mx-auto text-center"
      >
        <p class="text-gray-500 mb-1" v-motion v-bind="slideUp(0)">SOLUTIONS</p>
        <h1 class="text-5xl font-bold" v-motion v-bind="slideUp(50)">
          Choose Profeed as your digital marketing agency
        </h1>
        <h3 class="text-lg text-gray-600 mt-4" v-motion v-bind="slideUp(100)">
          A subheading that addresses the what, the why we should care and
          hopefully some social proof.
        </h3>

        <div class="flex gap-2 my-8">
          <button
            class="h-10 px-4 bg-gray-900 text-white rounded-full"
            v-motion
            v-bind="slideUp(150)"
          >
            Contact Us
          </button>
          <button
            class="h-10 px-4 bg-gray-200 text-gray-900 rounded-full"
            v-motion
            v-bind="slideUp(200)"
          >
            Learn more
          </button>
        </div>
      </div>

      <div>
        <HerosSwiper />
      </div>
    </div>

    <div id="clients" class="max-w-7xl mx-auto p-4 py-32">
      <div class="grid grid-cols-5 gap-16 place-items-center">
        <div
          v-for="index in 10"
          :key="index"
          v-motion
          v-bind="slideUp(index * 50)"
        >
          <img :src="`/icon/Company Placeholder-${index}.svg`" alt="" />
        </div>
      </div>
    </div>

    <div id="about-us" class="max-w-7xl mx-auto p-4 pt-16 pb-32">
      <div class="grid grid-cols-2 gap-8 place-items-center">
        <div>
          <h1 class="text-5xl font-bold" v-motion v-bind="slideUp(0)">
            A catchy heading that brings some interest to visitors
          </h1>
          <p class="text-xl text-gray-600 my-4" v-motion v-bind="slideUp(50)">
            Tortor interdum condimentum nunc molestie quam lectus euismod
            pulvinar risus. Cursus in odio aenean.
          </p>
          <button
            class="h-10 px-6 bg-gray-900 text-white rounded-full flex items-center gap-3"
            v-motion
            v-bind="slideUp(200)"
          >
            Learn more
            <svg
              xmlns="http://www.w3.org/2000/svg"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              class="w-6 h-6"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
              />
            </svg>
          </button>
        </div>
        <div>
          <img
            src="/img/worker.png"
            alt=""
            class="rounded-3xl"
            v-motion
            v-bind="slideUp(100)"
          />
        </div>
      </div>
    </div>

    <div id="services" class="bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 py-16">
        <h1 class="text-5xl font-bold mb-8" v-motion v-bind="slideUp(0)">
          Our Services
        </h1>

        <div class="grid grid-cols-3 gap-8">
          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(50)">
            <img class="w-16 h-16 mb-4" src="/icon/social-media.png" alt="" />
            <h1 class="font-semibold text-xl">Social Media Management</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>

          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(100)">
            <img class="w-16 h-16 mb-4" src="/icon/event.png" alt="" />
            <h1 class="font-semibold text-xl">Event Management</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>

          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(150)">
            <img class="w-16 h-16 mb-4" src="/icon/branding.png" alt="" />
            <h1 class="font-semibold text-xl">Branding</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>

          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(200)">
            <img class="w-16 h-16 mb-4" src="/icon/social-media.png" alt="" />
            <h1 class="font-semibold text-xl">Social Media Management</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>

          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(250)">
            <img class="w-16 h-16 mb-4" src="/icon/event.png" alt="" />
            <h1 class="font-semibold text-xl">Event Management</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>

          <div class="p-6 bg-white rounded-2xl" v-motion v-bind="slideUp(300)">
            <img class="w-16 h-16 mb-4" src="/icon/branding.png" alt="" />
            <h1 class="font-semibold text-xl">Branding</h1>
            <p class="text-gray-600 mt-1">
              Tortor interdum condimentum nunc molestie quam lectus euismod
              pulvinar risus. Cursus in odio aenean.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
