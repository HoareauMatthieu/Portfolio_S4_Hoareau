<template class="container h-screen overflow-hidden 0">
  <main>
    <div class="mt-56">
      <img src="public/image/Stuff/profilpic.jpg" alt="Description de l'image" class="mr-auto ml-auto h-auto w-72 object-cover" />
      <h1 class="mt-4 text-center text-3xl uppercase">Fringz - Matthieu HOAREAU</h1>
      <p class="text-center text-sm">“L'unique chose dont le monde n'aura jamais assez est l'exagération.”</p>
      <p class="text-center text-sm">Salvador Dali</p>
    </div>

    <p class="absolute top-28 right-4 p-4 underline"><a href="https://www.instagram.com/7fringz/">Instagram</a></p>
    <p class="absolute top-36 right-4 p-4 underline"><a href="https://twitter.com/7Fringz">Twitter</a></p>
    <p class="absolute bottom-0 right-4 p-4">Mentions légales</p>
    <p class="absolute bottom-0 left-4 p-4">PORTFOLIO FRINGZ</p>
  </main>
</template>

<script>
import IconLogo from "../components/icons/IconLogo.vue";
import Bouton from "../components/icons/Bouton.vue";
export default {
  components: { IconLogo, Bouton },
};
</script>