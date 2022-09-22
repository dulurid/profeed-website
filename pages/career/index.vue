<template>
  <div class="relative overflow-hidden bg-white">
    <div class="pt-16 pb-80 sm:pt-24 sm:pb-40 lg:pt-40 lg:pb-48">
      <div class="relative mx-auto max-w-7xl px-4 sm:static sm:px-6 lg:px-8">
        <div class="sm:max-w-lg">
          <h1
            v-motion
            v-bind="useSlideUpMotion(0)"
            class="font text-4xl font-bold tracking-tight text-gray-900 sm:text-6xl"
          >
            Finding the career path for you
          </h1>
          <p
            class="mt-4 text-xl text-gray-500"
            v-motion
            v-bind="useSlideUpMotion(50)"
          >
            This year, our new summer collection will shelter you from the harsh
            elements of a world that doesn't care if you live or die.
          </p>
        </div>
        <div>
          <div class="mt-10">
            <!-- Decorative image grid -->
            <div
              aria-hidden="true"
              class="pointer-events-none lg:absolute lg:inset-y-0 lg:mx-auto lg:w-full lg:max-w-7xl"
            >
              <div
                class="absolute transform sm:left-1/2 sm:top-0 sm:translate-x-8 lg:left-1/2 lg:top-1/2 lg:-translate-y-1/2 lg:translate-x-8"
              >
                <div class="flex items-center space-x-6 lg:space-x-8">
                  <div
                    class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8"
                  >
                    <div
                      class="h-64 w-44 overflow-hidden rounded-lg sm:opacity-0 lg:opacity-100"
                    >
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(50)"
                        src="https://images.unsplash.com/photo-1579389248774-07907f421a6b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(200)"
                        src="https://images.unsplash.com/photo-1521737711867-e3b97375f902?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                  </div>
                  <div
                    class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8"
                  >
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(100)"
                        src="https://images.unsplash.com/photo-1542744173-8e7e53415bb0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(250)"
                        src="https://images.unsplash.com/photo-1513470270416-d3ff6f16b22f?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(350)"
                        src="https://images.unsplash.com/photo-1513258496099-48168024aec0?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=2940&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                  </div>
                  <div
                    class="grid flex-shrink-0 grid-cols-1 gap-y-6 lg:gap-y-8"
                  >
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(150)"
                        src="https://images.unsplash.com/photo-1488751045188-3c55bbf9a3fa?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                    <div class="h-64 w-44 overflow-hidden rounded-lg">
                      <img
                        v-motion
                        v-bind="useSlideUpMotion(300)"
                        src="https://images.unsplash.com/photo-1536148935331-408321065b18?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1887&q=80"
                        alt=""
                        class="h-full w-full object-cover object-center"
                      />
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
