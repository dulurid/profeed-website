<script setup>
useHead({
  title: 'Profeed',
  viewport: 'width=device-width, initial-scale=1, maximum-scale=1',
  charset: 'utf-8',
  meta: [{ name: 'description', content: 'My amazing site.' }],
  bodyAttrs: {
    class: 'test',
  },
})

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
        type: 'spring',
        stiffness: 350,
        damping: 20,
        delay: delay,
      },
    },
  }
}
</script>

<template>
  <div>
    <div id="heros" class="max-w-7xl mx-auto p-4 pt-16">
      <div
        class="flex flex-col items-center justify-center max-w-xl mx-auto text-center"
      >
        <p class="text-gray-500 mb-1" v-motion v-bind="slideUp(0)">SOLUTIONS</p>

        <div
          class="relative group hidden lg:flex"
          v-motion
          v-bind="useSlideUpMotion(0)"
        >
          <div
            class="absolute transitiona-all duration-1000 opacity-25 -inset-px bg-gradient-to-r from-[#44BCFF] via-[#FF44EC] to-[#FF675E] rounded-xl blur-2xl filter"
          ></div>
          <h1 class="text-5xl font-bold" v-motion v-bind="slideUp(50)">
            Choose Profeed as your digital marketing agency
          </h1>
        </div>

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

    <section class="py-10 bg-gray-50 sm:py-16 lg:py-24">
      <div class="max-w-5xl px-4 mx-auto sm:px-6 lg:px-8">
        <div
          class="grid items-center grid-cols-1 gap-y-6 md:grid-cols-2 md:gap-x-20"
        >
          <div class="">
            <h2
              class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl"
            >
              Grow business with Celebration.
            </h2>
            <p class="mt-4 text-base leading-relaxed text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia consequat duis enim velit mollit.
              Exercitation veniam consequat sunt nostrud amet.
            </p>
          </div>

          <div class="relative pl-20 pr-6 sm:pl-6 md:px-0">
            <div class="relative w-full max-w-xs mt-4 mb-10 ml-auto">
              <img
                class="ml-auto"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/1/person.jpg"
                alt=""
              />

              <img
                class="absolute -top-4 -left-12"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/1/wavey-lines.svg"
                alt=""
              />

              <div class="absolute -bottom-10 -left-16">
                <div class="bg-yellow-300">
                  <div class="px-8 py-10">
                    <span
                      class="block text-4xl font-bold text-black lg:text-5xl"
                    >
                      53%
                    </span>
                    <span class="block mt-2 text-base leading-tight text-black">
                      High Conversions<br />Everything
                    </span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="py-16 bg-white">
      <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <div class="grid items-stretch gap-y-10 md:grid-cols-2 md:gap-x-20">
          <div class="relative grid grid-cols-2 gap-6 mt-10 md:mt-0">
            <div class="overflow-hidden aspect-w-3 aspect-h-4">
              <img
                class="object-cover object-top origin-top scale-150"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/team-work.jpg"
                alt=""
              />
            </div>

            <div class="relative">
              <div class="h-full overflow-hidden aspect-w-3 aspect-h-4">
                <img
                  class="object-cover scale-150 lg:origin-bottom-right"
                  src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/woman-working-on-laptop.jpg"
                  alt=""
                />
              </div>

              <div
                class="absolute inset-0 grid w-full h-full place-items-center"
              >
                <button
                  type="button"
                  class="inline-flex items-center justify-center w-12 h-12 text-blue-600 bg-white rounded-full shadow-md lg:w-20 lg:h-20"
                >
                  <svg
                    class="w-6 h-6 lg:w-8 lg:h-8"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="currentColor"
                  >
                    <path
                      d="M8 6.82v10.36c0 .79.87 1.27 1.54.84l8.14-5.18c.62-.39.62-1.29 0-1.69L9.54 5.98C8.87 5.55 8 6.03 8 6.82z"
                    />
                  </svg>
                </button>
              </div>
            </div>

            <div class="absolute -translate-x-1/2 left-1/2 -top-16">
              <img
                class="w-32 h-32"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/round-text.png"
                alt=""
              />
            </div>
          </div>

          <div class="flex flex-col items-start xl:px-16">
            <h2
              class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl"
            >
              Grow business with Celebration.
            </h2>
            <p class="mt-4 text-base leading-relaxed text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia consequat duis enim velit mollit.
              Exercitation veniam consequat sunt nostrud amet.
            </p>

            <a
              href="#"
              title=""
              class="inline-flex items-center justify-center px-5 py-4 mt-8 text-base font-semibold text-white transition-all duration-200 rounded-md hover:opacity-90 focus:opacity-90 lg:mt-auto bg-gradient-to-r from-fuchsia-600 to-blue-600"
              role="button"
            >
              Get started now
              <svg
                class="w-5 h-5 ml-8 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </section>
    <section class="py-16 bg-white">
      <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <div class="grid items-stretch gap-y-10 md:grid-cols-2 md:gap-x-20">
          <div class="flex flex-col items-start xl:px-16">
            <h2
              class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl"
            >
              Grow business with Celebration.
            </h2>
            <p class="mt-4 text-base leading-relaxed text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia consequat duis enim velit mollit.
              Exercitation veniam consequat sunt nostrud amet.
            </p>

            <a
              href="#"
              title=""
              class="inline-flex items-center justify-center px-5 py-4 mt-8 text-base font-semibold text-white transition-all duration-200 rounded-md hover:opacity-90 focus:opacity-90 lg:mt-auto bg-gradient-to-r from-fuchsia-600 to-blue-600"
              role="button"
            >
              Get started now
              <svg
                class="w-5 h-5 ml-8 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>

          <div class="relative grid grid-cols-2 gap-6 mt-10 md:mt-0">
            <div class="overflow-hidden aspect-w-3 aspect-h-4">
              <img
                class="object-cover object-top origin-top scale-150"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/team-work.jpg"
                alt=""
              />
            </div>

            <div class="relative">
              <div class="h-full overflow-hidden aspect-w-3 aspect-h-4">
                <img
                  class="object-cover scale-150 lg:origin-bottom-right"
                  src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/woman-working-on-laptop.jpg"
                  alt=""
                />
              </div>

              <div
                class="absolute inset-0 grid w-full h-full place-items-center"
              >
                <button
                  type="button"
                  class="inline-flex items-center justify-center w-12 h-12 text-blue-600 bg-white rounded-full shadow-md lg:w-20 lg:h-20"
                >
                  <svg
                    class="w-6 h-6 lg:w-8 lg:h-8"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="currentColor"
                  >
                    <path
                      d="M8 6.82v10.36c0 .79.87 1.27 1.54.84l8.14-5.18c.62-.39.62-1.29 0-1.69L9.54 5.98C8.87 5.55 8 6.03 8 6.82z"
                    />
                  </svg>
                </button>
              </div>
            </div>

            <div class="absolute -translate-x-1/2 left-1/2 -top-16">
              <img
                class="w-32 h-32"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/round-text.png"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </section>
    <section class="py-16 bg-white">
      <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <div class="grid items-stretch gap-y-10 md:grid-cols-2 md:gap-x-20">
          <div class="relative grid grid-cols-2 gap-6 mt-10 md:mt-0">
            <div class="overflow-hidden aspect-w-3 aspect-h-4">
              <img
                class="object-cover object-top origin-top scale-150"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/team-work.jpg"
                alt=""
              />
            </div>

            <div class="relative">
              <div class="h-full overflow-hidden aspect-w-3 aspect-h-4">
                <img
                  class="object-cover scale-150 lg:origin-bottom-right"
                  src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/woman-working-on-laptop.jpg"
                  alt=""
                />
              </div>

              <div
                class="absolute inset-0 grid w-full h-full place-items-center"
              >
                <button
                  type="button"
                  class="inline-flex items-center justify-center w-12 h-12 text-blue-600 bg-white rounded-full shadow-md lg:w-20 lg:h-20"
                >
                  <svg
                    class="w-6 h-6 lg:w-8 lg:h-8"
                    xmlns="http://www.w3.org/2000/svg"
                    viewBox="0 0 24 24"
                    fill="currentColor"
                  >
                    <path
                      d="M8 6.82v10.36c0 .79.87 1.27 1.54.84l8.14-5.18c.62-.39.62-1.29 0-1.69L9.54 5.98C8.87 5.55 8 6.03 8 6.82z"
                    />
                  </svg>
                </button>
              </div>
            </div>

            <div class="absolute -translate-x-1/2 left-1/2 -top-16">
              <img
                class="w-32 h-32"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/features/2/round-text.png"
                alt=""
              />
            </div>
          </div>

          <div class="flex flex-col items-start xl:px-16">
            <h2
              class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl"
            >
              Grow business with Celebration.
            </h2>
            <p class="mt-4 text-base leading-relaxed text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia consequat duis enim velit mollit.
              Exercitation veniam consequat sunt nostrud amet.
            </p>

            <a
              href="#"
              title=""
              class="inline-flex items-center justify-center px-5 py-4 mt-8 text-base font-semibold text-white transition-all duration-200 rounded-md hover:opacity-90 focus:opacity-90 lg:mt-auto bg-gradient-to-r from-fuchsia-600 to-blue-600"
              role="button"
            >
              Get started now
              <svg
                class="w-5 h-5 ml-8 -mr-1"
                xmlns="http://www.w3.org/2000/svg"
                viewBox="0 0 20 20"
                fill="currentColor"
              >
                <path
                  fill-rule="evenodd"
                  d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
                  clip-rule="evenodd"
                />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
