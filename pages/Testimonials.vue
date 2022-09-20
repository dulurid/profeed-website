<script setup>
useHead({
  title: "Profeed",
  viewport: "width=device-width, initial-scale=1, maximum-scale=1",
  charset: "utf-8",
  meta: [{ name: "description", content: "My amazing site." }],
  bodyAttrs: {
    class: "Testimonials",
  },
});
</script>
<template>
  <section>
    <div class="container flex flex-col px-5 py-10 mx-auto md:flex-row">
      <div
        class="flex flex-col py-5 text-center lg:flex-grow md:w-1/2 lg:px-24 md:items-start md:text-left"
      >
        <h2 class="mb-4 text-lg font-bold text-gray-600">
          BECOME A LEGENDARY DESIGNER
        </h2>

        <h1 class="mb-4 font-bold text-gray-900 sm:text-5xl">
          We have done with several projects
        </h1>
        <p class="mb-8 pb-14">
          A subheading that addresses the what, the why we should care and
          hopefully some social proof.
        </p>

        <div class="w-full rounded-xl">
          <div class="text-sm font-bold rounded-lg">
            <div class="grid h-40 grid-cols-2 gap-4">
              <div
                class="flex items-center p-4 bg-white rounded-lg drop-shadow-lg hover:bg-gray-200"
              >
                <img
                  alt="People icon"
                  srcset="
                    https://img.icons8.com/ultraviolet/2x/conference-call.png 2x
                  "
                />

                <div class="mx-auto">
                  <h1 class="font-bold md:text-2xl">200+</h1>
                  <p class="text-sm text-gray-500">happies clients</p>
                </div>

                <!-- 2 -->
              </div>
              <!-- 2 -->
              <div
                class="flex items-center p-4 bg-white rounded-lg drop-shadow-lg hover:bg-gray-200"
              >
                <img
                  alt="Increase icon"
                  srcset="https://img.icons8.com/ultraviolet/2x/bullish.png 2x"
                />

                <div class="mx-auto">
                  <h1 class="font-bold md:text-2xl">300+</h1>
                  <p class="text-sm text-gray-500">Projects Completed</p>
                </div>

                <!-- 2 -->
              </div>
              <!-- 3 -->
              <div
                class="flex items-center p-4 bg-white rounded-lg drop-shadow-lg hover:bg-gray-200"
              >
                <img
                  alt="Download Resume icon"
                  srcset="
                    https://img.icons8.com/ultraviolet/2x/open-resume.png 2x
                  "
                />

                <div class="mx-auto">
                  <h1 class="font-bold md:text-2xl">100M+</h1>
                  <p class="text-sm text-gray-500">Apps Downloads</p>
                </div>
              </div>
              <!-- 4 -->
              <div
                class="flex items-center p-4 bg-white rounded-lg drop-shadow-lg hover:bg-gray-200"
              >
              <img alt="Blue Internet icon" srcset="https://img.icons8.com/ultraviolet/2x/internet--v1.png 2x">

                <div class="mx-auto">
                  <h1 class="font-bold md:text-2xl">20+</h1>
                  <p class="text-sm text-gray-500">Country served</p>
                </div>

              
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="w-5/6 mb-10 lg:max-w-lg lg:w-[720px] md:w-1/2 md:mb-0">
        <img
          class="object-cover object-center rounded"
          alt="hero"
          src="https://images.unsplash.com/photo-1493020258366-be3ead1b3027?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8N3x8d29yayUyMGZpbmFuY2V8ZW58MHwyfDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
        />
      </div>
    </div>
  </section>
</template>
