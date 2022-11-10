<script setup>
const projects = [
  'https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80',
  'https://images.unsplash.com/photo-1522204523234-8729aa6e3d5f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80',
  'https://images.unsplash.com/photo-1459184070881-58235578f004?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=870&q=80',
  'https://images.unsplash.com/photo-1658863025658-4a259cc68fc9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=725&q=80',
]
const text = ['Website Programing']
console.log(text)
</script>

<template>
  <div>
    <section class="py-10 bg-white sm:py-16 lg:py-24">
      <div class="px-4 mx-auto max-w-7xl sm:px-6 lg:px-8">
        <div
          class="grid items-center grid-cols-1 lg:grid-cols-2 gap-x-12 xl:gap-x-24 gap-y-12"
        >
          <div class="relative lg:mb-12">
            <img
              class="absolute -right-0 -bottom-8 xl:-bottom-12 xl:-right-4"
              src="https://cdn.rareblocks.xyz/collection/celebration/images/content/3/dots-pattern.svg"
              alt=""
            />
            <div class="pl-12 pr-6">
              <img
                class="relative"
                src="https://cdn.rareblocks.xyz/collection/celebration/images/content/3/girl-working-on-laptop.jpg"
                alt=""
              />
            </div>
            <div class="absolute left-0 pr-12 bottom-8 xl:bottom-20">
              <div
                class="max-w-xs bg-blue-600 rounded-lg sm:max-w-md xl:max-w-md"
              >
                <div class="px-3 py-4 sm:px-5 sm:py-8">
                  <div class="flex items-start">
                    <p class="text-3xl sm:text-4xl">👋</p>
                    <blockquote class="ml-5">
                      <p class="text-sm font-medium text-white sm:text-lg">
                        “You made it so simple. My new site is so much faster
                        and easier to work with than my old site.”
                      </p>
                    </blockquote>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <div class="2xl:pl-16">
            <h2
              class="text-3xl font-bold leading-tight text-black sm:text-4xl lg:text-5xl lg:leading-tight"
            >
              We make things easy for projects.
            </h2>
            <p class="text-xl leading-relaxed text-gray-900 mt-9">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint. Velit officia conse duis enim velit mollit.
              Exercitation veniam.
            </p>
            <p class="mt-6 text-xl leading-relaxed text-gray-900">
              Velit officia conse duis enim velit mollit. Exercit ation veniam
              consequat sunt nostrud amet.
            </p>
          </div>
        </div>
      </div>
    </section>

    <section class="py-10 bg-white sm:py-16 lg:py-20">
      <div class="px-4 mx-auto sm:px-6 lg:px-8 max-w-7xl">
        <div
          class="grid grid-cols-1 lg:grid-cols-3 gap-y-12 lg:gap-x-8 xl:gap-x-20"
        >
          <div>
            <h3 class="text-2xl font-semibold text-black">London Office</h3>
            <p class="mt-3 text-base text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>

            <div class="mt-10 space-y-5">
              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  8502 Preston Rd. Inglewood, Maine 98380, USA
                </span>
              </div>

              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  sales@example.com
                </span>
              </div>
            </div>
          </div>

          <div>
            <h3 class="text-2xl font-semibold text-black">New York Office</h3>
            <p class="mt-3 text-base text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>

            <div class="mt-10 space-y-5">
              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  4517 Washington Ave. Manchester, Kentucky 39495
                </span>
              </div>

              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  support@example.com
                </span>
              </div>
            </div>
          </div>

          <div>
            <h3 class="text-2xl font-semibold text-black">Singapore Office</h3>
            <p class="mt-3 text-base text-gray-600">
              Amet minim mollit non deserunt ullamco est sit aliqua dolor do
              amet sint.
            </p>

            <div class="mt-10 space-y-5">
              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z"
                  />
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  3517 W. Gray St. Utica, Pennsylvania 57867
                </span>
              </div>

              <div class="flex items-start">
                <svg
                  class="flex-shrink-0 text-blue-600 w-7 h-7"
                  xmlns="http://www.w3.org/2000/svg"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="1.5"
                    d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"
                  />
                </svg>
                <span class="block ml-3 text-base font-medium text-gray-900">
                  contact@example.com
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
