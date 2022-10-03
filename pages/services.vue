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
                class="h-10 px-4 bg-gray-900 text-white rounded-full"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                Get Started
              </button>
            </div>
          </div>
        </div>

        <div class="w-1/2 h-[600px]" v-motion v-bind="useSlideUpMotion(150)">
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

    <section class="w-full py-20 bg-gray-50">
      <div class="px-10 mx-auto max-w-7xl">
        <div class="px-10 mb-8 space-y-5 lg:px-0 lg:text-center lg:mb-16">
          <h2
            class="text-4xl font-bold sm:text-5xl"
            v-motion
            v-bind="useSlideUpMotion(0)"
          >
            Our Services
          </h2>
        </div>
        <div class="grid overflow-hidden lg:rounded-xl">
          <div class="grid items-center lg:grid-cols-2">
            <div
              class="flex flex-col items-start justify-center h-full py-16 pl-16 pr-16 space-y-4 bg-white lg:pr-20 lg:py-0"
            >
              <h3
                class="text-2xl font-semibold sm:text-4xl"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                Social Media
              </h3>
              <p
                class="text-lg text-gray-600"
                v-motion
                v-bind="useSlideUpMotion(200)"
              >
                A beautiful drag and drop interface that allows you to create
                the landing page of your dreams. Our templates are designed for
                maximum conversion and the best user experience.
              </p>
            </div>
            <div class="overflow-hidden bg-gray-100 h-96">
              <img
                v-motion
                v-bind="useSlideUpMotion(50)"
                src="https://images.unsplash.com/photo-1643503640904-75c1a2093570?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                class="object-cover w-full h-full"
                alt=""
              />
            </div>
          </div>
          <div class="grid items-center lg:grid-cols-2">
            <div
              class="order-last overflow-hidden bg-gray-100 h-96 lg:order-first"
            >
              <img
                v-motion
                v-bind="useSlideUpMotion(0)"
                src="https://images.unsplash.com/photo-1541506618330-7c369fc759b5?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1665&amp;q=80"
                class="object-cover w-full h-full"
                alt=""
              />
            </div>
            <div
              class="flex flex-col items-start justify-center h-full py-16 pl-16 pr-16 space-y-4 bg-white lg:pr-20 lg:py-0"
            >
              <h3
                class="text-2xl font-semibold sm:text-4xl"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                Branding and Marketing
              </h3>
              <p
                class="text-lg text-left text-gray-600"
                v-motion
                v-bind="useSlideUpMotion(200)"
              >
                Delight your users with the most intuitive and easy to follow
                designs that will help you convert those visitors into paying
                customers.
              </p>
            </div>
          </div>
          <div class="grid items-center lg:grid-cols-2">
            <div
              class="flex flex-col items-start justify-center h-full py-16 pl-16 pr-16 space-y-4 bg-white lg:pr-20 lg:py-0"
            >
              <h3
                class="text-2xl font-semibold sm:text-4xl"
                v-motion
                v-bind="useSlideUpMotion(100)"
              >
                Event Management
              </h3>
              <p
                class="text-lg text-gray-600"
                v-motion
                v-bind="useSlideUpMotion(200)"
              >
                All our templates are easy to customize and make your own. It
                has never been easier to integrate beautiful designs into your
                web applications.
              </p>
            </div>
            <div class="bg-gray-100 h-96">
              <img
                v-motion
                v-bind="useSlideUpMotion(0)"
                src="https://images.unsplash.com/photo-1492684223066-81342ee5ff30?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                class="object-cover w-full h-full"
                alt=""
              />
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
