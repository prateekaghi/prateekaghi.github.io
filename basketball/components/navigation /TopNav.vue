<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Exo:wght@700&display=swap");
.fontExo {
  font-family: "Exo", sans-serif;
}
.router-link-exact-active {
  color: #f28c00;
}
</style>
<script setup>
const links = [
  {
    name: "Home",
    link: "/",
  },
  {
    name: "About Us",
    link: "/about",
  },
  {
    name: "Our Training",
    link: "/training",
  },
  {
    name: "Camps",
    link: "/camps",
  },
  {
    name: "Locations",
    link: "/location",
  },
  {
    name: "Schedule",
    link: "/schedule",
  },
  {
    name: "Contact Us",
    link: "/contact",
  },
];
</script>

<template>
  <div class="flex absolute justify-between z-50 w-full">
    <img src="~/public/images/logo.png" class="h-36 mx-24" alt="" />
    <div class="flex mx-24">
      <NuxtLink
        v-for="link in links"
        class="fontExo text-white self-center mx-5 text-base"
        :to="link.link"
        >{{ link.name }}</NuxtLink
      >
      <button
        class="fontExo bg-[#F28C00] h-12 self-center text-[#F0F0F0] text-base w-36"
      >
        My Account
      </button>
    </div>
  </div>
</template>
