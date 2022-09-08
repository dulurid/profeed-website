<script setup>
const slideVisibleLeft = (delay) => {
  return {
    initial: {
      x: -100,
      opacity: 0,
    },
    visible: {
      x: 0,
      opacity: 1,
      transition: {
        delay: delay,
      },
    },
  };
};

const slideRight = {
  initial: {
    x: 100,
    opacity: 0,
  },
  enter: {
    x: 0,
    opacity: 1,
  },
};
</script>

<template>
  <main>
    <div class="flex justify-between max-w-7xl mx-auto px-4 py-8">
      <div v-motion v-bind="slideVisibleLeft(0)">
        <svg
          width="32"
          height="32"
          viewBox="0 0 32 32"
          fill="none"
          xmlns="http://www.w3.org/2000/svg"
        >
          <rect width="32" height="32" rx="6" fill="#111827" />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M10.7614 16.1116C10.8112 16.2267 10.9087 16.3157 11.0283 16.3555L15.9071 17.9789C15.9682 17.9992 16.032 18.0057 16.0941 17.9988C16.1531 17.9922 16.2104 17.9736 16.2623 17.9432L20.4792 15.4739C20.5921 15.4078 20.6669 15.2935 20.6823 15.1637C20.6978 15.0339 20.6521 14.903 20.5584 14.8084L14.7636 8.96034C14.6646 8.86051 14.5243 8.81308 14.3862 8.83334C14.2485 8.85354 14.1305 8.93874 14.0697 9.062L10.7689 15.756C10.7143 15.8667 10.7116 15.9964 10.7614 16.1116Z"
            fill="#FFCC02"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M16.3283 19.2449C16.3051 19.0835 16.1918 18.9471 16.036 18.8928L3.16487 14.403C2.98636 14.3407 2.79015 14.399 2.67958 14.5473C2.5691 14.6956 2.56966 14.8997 2.68101 15.0522L9.08102 23.8173C9.17777 23.9498 9.33541 24.0138 9.48728 23.9969C9.55256 23.9896 9.61675 23.9674 9.67461 23.9292L16.1457 19.6539C16.2809 19.5646 16.3515 19.4062 16.3283 19.2449Z"
            fill="#EFAE07"
          />
          <path
            fill-rule="evenodd"
            clip-rule="evenodd"
            d="M28.4941 11.5194C28.3477 11.3977 28.1408 11.3824 27.983 11.4816L9.33053 23.1934C9.16168 23.2994 9.09165 23.5083 9.16171 23.6975C9.23173 23.8867 9.42312 24.0049 9.62329 23.9836L24.1624 22.4315L24.1645 22.4313C24.3195 22.414 24.4514 22.3164 24.5092 22.1735L28.6225 12.0135C28.6924 11.841 28.6404 11.641 28.4941 11.5194Z"
            fill="#FFCC02"
          />
        </svg>
      </div>

      <ul class="flex gap-8">
        <li v-motion v-bind="slideVisibleLeft(50)">Home</li>
        <li v-motion v-bind="slideVisibleLeft(100)">Services</li>
        <li v-motion v-bind="slideVisibleLeft(150)">Portofolio</li>
        <li v-motion v-bind="slideVisibleLeft(200)">Testimonials</li>
        <li v-motion v-bind="slideVisibleLeft(250)">Career</li>
        <li v-motion v-bind="slideVisibleLeft(300)">About</li>
      </ul>

      <div v-motion v-bind="slideVisibleLeft(400)">
        <img src="/us.svg" alt="" />
      </div>
    </div>

    <slot />
  </main>
</template>
