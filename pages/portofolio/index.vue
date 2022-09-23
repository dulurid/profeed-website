<script setup>
const projects = [
  'https://images.unsplash.com/photo-1633793566023-a74b74104acb?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
  'https://images.unsplash.com/photo-1597045566677-8cf032ed6634?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1611138300749-9338ed615f56?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
  'https://images.unsplash.com/photo-1632312527047-61fc22faed62?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1611138290962-2c550ffd4002?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80',
  'https://images.unsplash.com/photo-1604586398467-32924c78b879?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80',
];
</script>

<template>
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

    <div class="bg-gray-50 py-4">
      <section
        class="flex items-center justify-center py-20 bg-white min-w-screen"
      >
        <div class="px-16 bg-white">
          <div
            class="container flex flex-col items-start mx-auto lg:items-center"
          >
            <p
              v-motion
              v-bind="useSlideUpMotion(0)"
              class="relative flex items-start justify-start w-full text-lg font-bold tracking-wider text-purple-500 uppercase lg:justify-center lg:items-center"
              data-primary="purple-500"
            >
              Don't just take our word for it
            </p>

            <h2
              v-motion
              v-bind="useSlideUpMotion(50)"
              class="relative flex items-start justify-start w-full max-w-3xl text-5xl font-bold lg:justify-center"
            >
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="currentColor"
                class="absolute right-0 hidden w-12 h-12 -mt-2 -mr-16 text-gray-200 lg:inline-block"
                viewBox="0 0 975.036 975.036"
              >
                <path
                  d="M925.036 57.197h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.399 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l36 76c11.6 24.399 40.3 35.1 65.1 24.399 66.2-28.6 122.101-64.8 167.7-108.8 55.601-53.7 93.7-114.3 114.3-181.9 20.601-67.6 30.9-159.8 30.9-276.8v-239c0-27.599-22.401-50-50-50zM106.036 913.497c65.4-28.5 121-64.699 166.9-108.6 56.1-53.7 94.4-114.1 115-181.2 20.6-67.1 30.899-159.6 30.899-277.5v-239c0-27.6-22.399-50-50-50h-304c-27.6 0-50 22.4-50 50v304c0 27.601 22.4 50 50 50h145.5c-1.9 79.601-20.4 143.3-55.4 191.2-27.6 37.8-69.4 69.1-125.3 93.8-25.7 11.3-36.8 41.7-24.8 67.101l35.9 75.8c11.601 24.399 40.501 35.2 65.301 24.399z"
                ></path>
              </svg>
              See what others are saying
            </h2>
            <div
              v-motion
              v-bind="useSlideUpMotion(75)"
              class="block w-full h-0.5 max-w-lg mt-6 bg-purple-100 rounded-full"
              data-primary="purple-600"
            ></div>

            <div class="items-center justify-center w-full mt-12 mb-4 lg:flex">
              <div
                v-motion
                v-bind="useSlideUpMotion(100)"
                class="flex flex-col items-start justify-start w-full h-auto mb-12 lg:w-1/3 lg:mb-0"
              >
                <div class="flex items-center justify-center">
                  <div
                    class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                  >
                    <img
                      src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1700&q=80"
                      class="object-cover w-full h-full"
                    />
                  </div>
                  <div class="flex flex-col items-start justify-center">
                    <h4 class="font-bold text-gray-800">John Doe</h4>
                    <p class="text-gray-600">CEO of Something</p>
                  </div>
                </div>
                <blockquote class="mt-8 text-lg text-gray-500">
                  "This is a no-brainer if you want to take your business to the
                  next level. If you are looking for the ultimate toolset, this
                  is it!"
                </blockquote>
              </div>
              <div
                v-motion
                v-bind="useSlideUpMotion(150)"
                class="flex flex-col items-start justify-start w-full h-auto px-0 mx-0 mb-12 border-l border-r border-transparent lg:w-1/3 lg:mb-0 lg:px-8 lg:mx-8 lg:border-gray-200"
              >
                <div class="flex items-center justify-center">
                  <div
                    class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                  >
                    <img
                      src="https://images.unsplash.com/photo-1544725176-7c40e5a71c5e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=2547&q=80"
                      class="object-cover w-full h-full"
                    />
                  </div>
                  <div class="flex flex-col items-start justify-center">
                    <h4 class="font-bold text-gray-800">Jane Doe</h4>
                    <p class="text-gray-600">CTO of Business</p>
                  </div>
                </div>
                <blockquote class="mt-8 text-lg text-gray-500">
                  "Thanks for creating this service. My life is so much easier.
                  Thanks for making such a great product."
                </blockquote>
              </div>
              <div
                v-motion
                v-bind="useSlideUpMotion(200)"
                class="flex flex-col items-start justify-start w-full h-auto lg:w-1/3"
              >
                <div class="flex items-center justify-center">
                  <div
                    class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                  >
                    <img
                      src="https://images.unsplash.com/photo-1545167622-3a6ac756afa4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1256&q=80"
                      class="object-cover w-full h-full"
                    />
                  </div>
                  <div class="flex flex-col items-start justify-center">
                    <h4 class="font-bold text-gray-800">John Smith</h4>
                    <p class="text-gray-600">Creator of Stuff</p>
                  </div>
                </div>
                <blockquote class="mt-8 text-lg text-gray-500">
                  "Packed with awesome content and exactly what I was looking
                  for. I would highly recommend this to anyone."
                </blockquote>
              </div>
            </div>
          </div>
        </div>
      </section>
    </div>

    <section class="w-full py-8 bg-white sm:py-12 md:py-16">
      <div class="px-10 mx-auto max-w-7xl">
        <div class="grid grid-cols-12 gap-6">
          <div
            v-for="(value, index) in projects"
            :key="value"
            class="relative col-span-12 mb-10 space-y-4 md:col-span-6 lg:col-span-4"
          >
            <div
              v-motion
              v-bind="useSlideUpMotion(index * 50)"
              class="relative block w-full h-64 overflow-hidden rounded"
            >
              <img
                class="object-cover object-center w-full h-full transition duration-500 ease-out transform scale-100 hover:scale-105"
                :src="value"
              />
            </div>
            <p
              v-motion
              v-bind="useSlideUpMotion(index * 75)"
              class="text-xs font-bold text-gray-400 uppercase"
            >
              SOCIAL MEDIA
            </p>
            <a
              v-motion
              v-bind="useSlideUpMotion(index * 100)"
              href="#_"
              class="block text-2xl font-medium leading-tight text-gray-700 hover:text-gray-900"
              >Learn How the Creator of Techstreet Crushed the Competition</a
            >
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
