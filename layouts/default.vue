<script setup>
const slideVisibleLeft = (delay) => {
  return {
    initial: {
      x: -100,
      opacity: 0,
    },
    visibleOnce: {
      x: 0,
      opacity: 1,
      transition: {
        delay: delay,
      },
    },
  }
}

const route = useRoute()

const getRouteName = computed(() => {
  return route.name
})
</script>

<template>
  <main>
    <div class="flex justify-between px-4 py-8 mx-auto max-w-7xl">
      <NuxtLink to="/" v-motion v-bind="slideVisibleLeft(0)">
        <Logo class="h-8 w-auto" />
      </NuxtLink>

      <ul class="flex gap-8">
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(50)">
          <NuxtLink to="/"> Home </NuxtLink>
          <span
            :class="
              getRouteName === 'index'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(100)">
          <NuxtLink to="/services"> Services </NuxtLink>
          <span
            :class="
              getRouteName === 'services'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(150)">
          <NuxtLink to="/portofolio"> Portofolio </NuxtLink>
          <span
            :class="
              getRouteName === 'portofolio'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(200)">
          <NuxtLink to="/testimonials">Testimonials</NuxtLink>
          <span
            :class="
              getRouteName === 'testimonials'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(250)">
          <NuxtLink to="/career"> Career </NuxtLink>
          <span
            :class="
              getRouteName === 'career'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
        <li class="flex flex-col group" v-motion v-bind="slideVisibleLeft(300)">
          <NuxtLink to="/about"> About </NuxtLink>
          <span
            :class="
              getRouteName === 'about'
                ? ''
                : 'opacity-0 group-hover:opacity-100 group-hover:translate-y-0 -translate-y-3'
            "
            class="border-b-[3px] border-b-gray-900 w-full rounded-full transform transition duration-300"
          ></span>
        </li>
      </ul>

      <div v-motion v-bind="slideVisibleLeft(400)">
        <img src="/us.svg" alt="" />
      </div>
    </div>

    <slot />

    <Footer />
  </main>
</template>
