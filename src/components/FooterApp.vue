<template >
  <div class="bg-black p-6">
    <div class="flex flex-row justify-between">
      <icon-logo class="h-16 w-16" />
    </div>
    <ul class="grid grid-cols-1 gap-10 p-5 text-center md:grid-cols-2">
      <li class="pb-5 text-sm text-white hover:font-black"><router-link to="/artiste">Artistes</router-link></li>

      <li class="pb-5 text-sm text-white hover:font-black"><router-link to="/programme">Programme</router-link></li>

      <li class="pb-5 text-sm text-white hover:font-black"><router-link to="/contact">Contact</router-link></li>

      <li class="pb-5 text-sm text-white hover:font-black"><router-link to="/mentions">Mentions légales</router-link></li>
    </ul>
    <hr class="m-4 border-t-2 border-indigo-100" />
    <div class="flex flex-col items-center">
      <p class="text-center text-sm text-white">©2023 Matthieu Hoareau Portfolio. All rights reserved</p>
      <div class="flex flex-row gap-5 pt-7">
        <instagram />
        <facebook />
        <twitter />
      </div>
    </div>
  </div>
</template>


<script >
import IconLogo from "../components/icons/IconLogo.vue";
import Sun from "../components/icons/Sun.vue";
import Facebook from "../components/icons/Facebook.vue";
import Twitter from "../components/icons/Twitter.vue";
import Instagram from "../components/icons/Instagram.vue";
export default {
  name: "Footer",
  components: {
    IconLogo,
    Sun,
    Facebook,
    Twitter,
    Instagram,
  },
};
</script>