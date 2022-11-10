<script setup>
const projects = [
  'https://images.unsplash.com/photo-1633793566023-a74b74104acb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
  'https://images.unsplash.com/photo-1597045566677-8cf032ed6634?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1611138300749-9338ed615f56?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
  'https://images.unsplash.com/photo-1632312527047-61fc22faed62?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1611138290962-2c550ffd4002?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1604586398467-32924c78b879?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
]
</script>

<template>
  <div>
    <div class="flex flex-col gap-16">
      <div id="heros" class="max-w-7xl mx-auto p-4">
        <div class="flex items-center gap-4">
          <div class="w-1/2">
            <div class="flex flex-col item max-w-xl mx-auto">
              <h1
                class="text-5xl font-bold"
                v-motion
                v-bind="useSlideUpMotion(50)"
              >
                We have done with several projects
              </h1>
              <h3
                class="text-lg text-gray-600 mt-4"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                A subheading that addresses the what, the why we should care and
                hopefully some social proof.
              </h3>

              <div
                class="flex gap-2 my-8"
                v-motion
                v-bind="useSlideUpMotion(150)"
              >
                <button class="h-10 px-4 bg-gray-900 text-white rounded-full">
                  Get Started
                </button>
              </div>
            </div>
          </div>

          <div class="w-1/2 h-[600px]" v-motion v-bind="useSlideUpMotion(0)">
            <div class="w-[600px]">
              <video-background
                poster="https://images.unsplash.com/photo-1553877522-43269d4ea984?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                src="https://prismic-io.s3.amazonaws.com/profeed/50ba1cb1-39c9-4099-9b3c-7feefff6abd8_AirPods+Pro+_+Rebuilt+from+the+sound+up+_+Apple.mp4"
                class="max-h-[600px] h-[600px] rounded-lg"
              >
              </video-background>
            </div>
          </div>
        </div>
      </div>

      <section class="py-12 bg-white sm:py-16 lg:py-20">
        <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
          <div class="max-w-md mx-auto text-center">
            <h2 class="text-3xl font-bold text-gray-900 sm:text-4xl font-pj">
              Read our blog
            </h2>
            <p class="mt-5 font-normal text-gray-600 font-pj">
              With lots of unique blocks, you can easily build a page without
              coding. Build your next landing page.
            </p>
          </div>

          <div
            class="grid max-w-3xl grid-cols-1 mx-auto mt-8 text-center sm:mt-16 sm:text-left sm:grid-cols-2 gap-y-8 gap-x-8 lg:gap-x-20"
          >
            <div class="relative group">
              <div class="overflow-hidden rounded-lg aspect-w-16 aspect-h-9">
                <img
                  class="object-cover w-full h-full transition-all duration-300 transform group-hover:scale-125"
                  src="https://cdn.rareblocks.xyz/collection/clarity/images/blog/1/blog-1.png"
                  alt=""
                />
              </div>
              <p class="mt-6 text-sm font-normal text-gray-600 font-pj">
                November 22, 2021
              </p>
              <p class="mt-4 text-xl font-bold text-gray-900 font-pj">
                How To Optimize Progressive Web Apps: Going Beyond The Basics
              </p>
              <a href="#" title="">
                <span class="absolute inset-0" aria-hidden="true"></span>
              </a>
            </div>

            <div class="relative group">
              <div class="overflow-hidden rounded-lg aspect-w-16 aspect-h-9">
                <img
                  class="object-cover w-full h-full transition-all duration-300 transform group-hover:scale-125"
                  src="https://cdn.rareblocks.xyz/collection/clarity/images/blog/1/blog-2.png"
                  alt=""
                />
              </div>
              <p class="mt-6 text-sm font-normal text-gray-600 font-pj">
                November 16, 2021
              </p>
              <p class="mt-4 text-xl font-bold text-gray-900 font-pj">
                How To Optimize Progressive Web Apps: Going Beyond The Basics
              </p>
              <a href="#" title="">
                <span class="absolute inset-0" aria-hidden="true"></span>
              </a>
            </div>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>
