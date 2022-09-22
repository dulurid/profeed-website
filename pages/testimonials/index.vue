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
        class="flex flex-col py-5 text-center lg:flex-grow md:w-1/2 lg:pr-24 md:items-start md:text-left"
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
                class="flex items-center p-4 bg-white border rounded-lg hover:bg-gray-200"
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
              </div>

              <div
                class="flex items-center p-4 bg-white border rounded-lg hover:bg-gray-200"
              >
                <img
                  alt="Increase icon"
                  srcset="https://img.icons8.com/ultraviolet/2x/bullish.png 2x"
                />

                <div class="mx-auto">
                  <h1 class="font-bold md:text-2xl">300+</h1>
                  <p class="text-sm text-gray-500">Projects Completed</p>
                </div>
              </div>

              <div
                class="flex items-center p-4 bg-white border rounded-lg hover:bg-gray-200"
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

              <div
                class="flex items-center p-4 bg-white border rounded-lg hover:bg-gray-200"
              >
                <img
                  alt="Blue Internet icon"
                  srcset="
                    https://img.icons8.com/ultraviolet/2x/internet--v1.png 2x
                  "
                />

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

    <!-- Slide 2 -->

    <div
      class="container flex flex-col py-10 pl-5 mx-auto lg:flex-grow md:flex-row"
    >
      <div class="w-full h-auto mb-10 md:mb-0">
        <div class="w-auto h-full">
          <img
            class="w-full h-auto rounded"
            alt="hero"
            src="https://images.unsplash.com/photo-1571844307880-751c6d86f3f3?ixlib=rb-1.2.1&amp;ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mnx8d29tZW4lMjBidXNpbmVzc3xlbnwwfDB8MHx8&amp;auto=format&amp;fit=crop&amp;w=500&amp;q=60"
          />
        </div>
      </div>

      <div class="w-full h-auto mb-10 md:mb-0">
        <div class="w-auto h-full pl-24">
          <p
            class="mb-8 text-4xl font-extrabold tracking-tight text-gray-900 sm:text-5xl md:text-4xl lg:text-5xl xl:text-xl"
          >
            <span class="block xl:inline">
              At Designership, they ship truly brilliant products! It’s easy to
              use and scale, and is really handy to customise for any projects.
            </span>
          </p>
          <p
            class="mx-auto mb-24 text-base text-neutral-500 sm:max-w-md md:max-w-3xl lg:text-lg"
          >
            Ac faucibus orci id quis consectetur laoreet sed. Enim congue
            molestie nam odio pulvinar ac ultricies. Elementum ut pellentesque
            volutpat mi. Faucibus sit posuere nisi aenean ultrices. Suscipit
            malesuada aenean nullam et sit dapibus eget a eu. Nisl tortor arcu
            et.
          </p>

          <p
            class="mx-auto text-base font-bold text-neutral-900 sm:max-w-md md:max-w-3xl lg:text-l"
          >
            PROFEED CEO
          </p>
          <p
            class="mx-auto text-base font-bold text-neutral-500 sm:max-w-md md:max-w-3xl lg:text-sm"
          >
            Founder, Benefeed & Profeed (BTC)
          </p>
        </div>
      </div>
    </div>
    <section>
      <div class="py-4 bg-gray-50">
        <section
          class="flex items-center justify-center py-20 bg-white min-w-screen"
        >
          <div class="px-16 bg-white">
            <div class="container flex flex-col items-start lg:items-center">
              <div class="items-center justify-center w-full mb-4 lg:flex">
                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg leading-relaxed text-gray-500">
                 
                    "Quis neque, eu et ipsum amet, vel et. Varius integer enim
                    pellentesque ornare pharetra faucibs arcu. 
                  
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1527980965255-d3b416303d12?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1700&q=80"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>

                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 mx-8 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg text-gray-500">
                    "Thanks for creating this service. My life is so much
                    easier. Thanks for making such a great product."
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=388&q=80"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>

                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg text-gray-500">
                    "Thanks for creating this service. My life is so much
                    easier. Thanks for making such a great product."
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1573497491765-dccce02b29df?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8Mzl8fHdvbWVuJTIwZmFjZXxlbnwwfHwwfHw%3D&auto=format&fit=crop&w=500&q=60"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>
              </div>

              <div class="items-center justify-center w-full mt-4 mb-4 lg:flex">
                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg text-gray-500">
                    "Thanks for creating this service. My life is so much
                    easier. Thanks for making such a great product."
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1560250097-0b93528c311a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NXx8bWVuJTIwYnVzaW5lc3N8ZW58MHx8MHx8&auto=format&fit=crop&w=500&q=60"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>

                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 mx-8 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg text-gray-500">
                    "Thanks for creating this service. My life is so much
                    easier. Thanks for making such a great product."
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1541101767792-f9b2b1c4f127?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8NDR8fHdvbWVufGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>

                <div
                  class="flex flex-col items-start justify-start w-full h-auto p-4 rounded-lg shadow-lg lg:w-1/3 lg:mb-0"
                >
                  <blockquote class="text-lg text-gray-500">
                    "Thanks for creating this service. My life is so much
                    easier. Thanks for making such a great product."
                  </blockquote>
                  <div class="flex items-center justify-center mt-8">
                    <div
                      class="w-16 h-16 mr-4 overflow-hidden bg-gray-200 rounded-full"
                    >
                      <img
                        src="https://images.unsplash.com/photo-1562788869-4ed32648eb72?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxzZWFyY2h8MjV8fG1lbiUyMGJ1c2luZXNzfGVufDB8fDB8fA%3D%3D&auto=format&fit=crop&w=500&q=60"
                        class="object-cover w-full h-full"
                        alt=""
                      />
                    </div>
                    <div class="flex flex-col items-start justify-center">
                      <h4 class="font-bold text-gray-800">John Doe</h4>
                      <p class="text-gray-600">CEO of Something</p>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </div>
    </section>
  </section>
</template>