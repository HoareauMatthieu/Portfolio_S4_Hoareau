<template class="container h-screen overflow-hidden 0">
  <main>
    <div class="pt-36">
      <span class="sr-only">Accueil</span>

      <div class="mx-12 hidden justify-between pt-32 text-sm uppercase lg:flex">
        <p>Matthieu Hoareau | Fringz</p>
        <p>Designer Digital</p>
        <p>Production Visuel</p>
        <p>Création d'identité Visuel</p>
      </div>

      <div class="absolute bottom-16 ml-3 mr-10 flex flex-col gap-12 lg:bottom-2 lg:mt-32 lg:flex-row">
        <h1 class="lg:hidden">Matthieu Hoareau | Fringz</h1>
        <!-- DIV 1 -->
        <div class="boxcontainer lg:w-1/2">
          <video autoplay loop muted><source src="/public/image/Bleu/bleu.mp4" type="video/mp4" /></video>
          <div class="banner">
            <h1 class="text-8xl font-bold leading-none lg:text-max">PORT FOLIO</h1>
          </div>
        </div>

        <!------------------------------------------------------------------------------------------------------------------------->
        <!-- DIV 3 (cachée) -->

        <div class="flex justify-between text-xs lg:hidden">
          <p>Designer Digital</p>
          <p>Production Visuel</p>
          <p>Création d'identité Visuel</p>
        </div>

        <!------------------------------------------------------------------------------------------------------------------------->

        <!-- DIV 2 -->
        <div class="grid-col-3 mr-auto ml-auto grid h-fit w-full gap-8 text-center uppercase lg:m-auto lg:w-1/2">
          <Bouton class="col-span-2 col-start-2 list-none text-xs sm:text-xl" id="button1">
            <li>
              <router-link to="/artdirection">--> Art Direction</router-link>
            </li>
          </Bouton>
          <Bouton class="col-span-2 list-none text-xs sm:text-xl">
            <li>
              <router-link to="/illu">--> Illustration Work</router-link>
            </li>
          </Bouton>
          <Bouton class="col-span-2 col-start-2 list-none text-xs sm:text-xl" id="button2">
            <li>
              <router-link to="/scolaire">--> School Project</router-link>
            </li>
          </Bouton>

          <Bouton class="col-span-2 list-none text-xs sm:text-xl">
            <li>
              <router-link to="/artiste">--> Travaux</router-link>
            </li>
          </Bouton>
        </div>
        <!------------------------------------------------------------------------------------------------------------------------->
      </div>
    </div>
    <p class="absolute bottom-0 right-0 p-4">Mentions légales</p>
  </main>
</template>

<script>
import IconLogo from "../components/icons/IconLogo.vue";
import Bouton from "../components/icons/Bouton.vue";
export default {
  components: { IconLogo, Bouton },
};
</script>

