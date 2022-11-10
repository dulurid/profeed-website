<template>
  <div class="flex flex-col gap-16">
    <div id="heros" class="max-w-7xl mx-auto p-4">
      <div class="flex items-center gap-4">
        <div class="w-1/2">
          <div class="flex flex-col item max-w-xl mx-auto">
            <h1
              class="text-5xl font-bold"
              v-motion
              v-bind="useSlideUpMotion(0)"
            >
              A headline to make an impact on visitors
            </h1>
            <h3
              class="text-lg text-gray-600 mt-4"
              v-motion
              v-bind="useSlideUpMotion(50)"
            >
              A subheading that addresses the what, the why we should care and
              hopefully some social proof.
            </h3>

            <div class="flex gap-2 my-8">
              <button
                class="h-10 px-4 bg-gray-900 text-white rounded-full flex items-center gap-2"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                Get Started

                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  viewBox="0 0 20 20"
                  fill="currentColor"
                  class="w-5 h-5"
                >
                  <path
                    fill-rule="evenodd"
                    d="M5.23 7.21a.75.75 0 011.06.02L10 11.168l3.71-3.938a.75.75 0 111.08 1.04l-4.25 4.5a.75.75 0 01-1.08 0l-4.25-4.5a.75.75 0 01.02-1.06z"
                    clip-rule="evenodd"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>

        <div class="w-1/2 h-[600px]" v-motion v-bind="useSlideUpMotion(150)">
          <div class="relative group">
            <div
              class="absolute transitiona-all duration-1000 opacity-30 -inset-px bg-gradient-to-r from-[#44BCFF] via-[#FF44EC] to-[#FF675E] rounded-xl blur-lg filter group-hover:opacity-50 group-hover:-inset-1 group-hover:duration-200"
            ></div>
            <div class="w-[600px]">
              <video-background
                poster="https://images.unsplash.com/photo-1484807352052-23338990c6c6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                src="https://prismic-io.s3.amazonaws.com/profeed/051e1c90-cfa0-496b-8795-db216f77b7c3_Introducing+Dynamic+Island+on+iPhone+14+Pro+_+Apple.mp4"
                class="max-h-[600px] h-[600px] rounded-lg"
              >
              </video-background>
            </div>
          </div>
        </div>
      </div>
    </div>

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
