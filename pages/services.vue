<template>
  <div class="flex flex-col gap-16">
    <div id="heros" class="max-w-7xl mx-auto p-4">
      <div class="flex items-center gap-4">
        <div class="w-1/2">
          <div class="flex flex-col item max-w-xl mx-auto">
            <h1 class="text-5xl font-bold">
              A headline to make an impact on visitors
            </h1>
            <h3 class="text-lg text-gray-600 mt-4">
              A subheading that addresses the what, the why we should care and
              hopefully some social proof.
            </h3>

            <div class="flex gap-2 my-8">
              <button class="h-10 px-4 bg-gray-900 text-white rounded-full">
                Get Started
              </button>
            </div>
          </div>
        </div>

        <div class="w-1/2 bg-black h-[600px]">
          <img
            class="h-[600px] w-full object-cover"
            src="https://images.unsplash.com/photo-1484807352052-23338990c6c6?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
            alt=""
          />
        </div>
      </div>
    </div>

    <section class="w-full py-20 bg-gray-50">
      <div class="px-10 mx-auto max-w-7xl">
        <div class="px-10 mb-8 space-y-5 lg:px-0 lg:text-center lg:mb-16">
          <h2 class="text-4xl font-bold sm:text-5xl">Our Services</h2>
        </div>
        <div class="grid overflow-hidden lg:rounded-xl">
          <div class="grid items-center lg:grid-cols-2">
            <div
              class="flex flex-col items-start justify-center h-full py-16 pl-16 pr-16 space-y-4 bg-white lg:pr-20 lg:py-0"
            >
              <h3 class="text-2xl font-semibold sm:text-4xl">Social Media</h3>
              <p class="text-lg text-gray-600">
                A beautiful drag and drop interface that allows you to create
                the landing page of your dreams. Our templates are designed for
                maximum conversion and the best user experience.
              </p>
            </div>
            <div class="overflow-hidden bg-gray-100 h-96">
              <img
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
                src="https://images.unsplash.com/photo-1541506618330-7c369fc759b5?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&amp;ixlib=rb-1.2.1&amp;auto=format&amp;fit=crop&amp;w=1665&amp;q=80"
                class="object-cover w-full h-full"
                alt=""
              />
            </div>
            <div
              class="flex flex-col items-start justify-center h-full py-16 pl-16 pr-16 space-y-4 bg-white lg:pr-20 lg:py-0"
            >
              <h3 class="text-2xl font-semibold sm:text-4xl">
                Branding and Marketing
              </h3>
              <p class="text-lg text-left text-gray-600">
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
              <h3 class="text-2xl font-semibold sm:text-4xl">
                Event Management
              </h3>
              <p class="text-lg text-gray-600">
                All our templates are easy to customize and make your own. It
                has never been easier to integrate beautiful designs into your
                web applications.
              </p>
            </div>
            <div class="bg-gray-100 h-96">
              <img
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
