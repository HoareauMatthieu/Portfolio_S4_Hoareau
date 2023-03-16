<template>
  <div class="mt-32 sm:ml-24 sm:mr-24">
    <div class="-mb-16 h-screen">
      <h1 class="mb-7 ml-6 text-4xl font-bold tracking-tight sm:ml-0 sm:text-7xl">Cap & Capuche</h1>
      <div class="h-4/6 bg-blue-400 sm:h-4/6">
        <img class="h-full w-full object-cover object-top" src="/public/image/UGB/UGBFINAL.jpg" alt="" />
      </div>
      <div class="flex justify-between">
        <div class="animate__animated animate__fadeIn p-4 text-sm">
          <p>Ugly Boy With A Pretty Hearth</p>
        </div>
        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-right">02/2023</p>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block sm:hidden">
      <h2 class="reveal ml-6 text-7xl font-bold tracking-tight sm:text-9xl">Critical eye.</h2>
      <div class="flex flex-col items-center">
        <div class="mt-3 w-9/12"><img class="object-cover" src="/public/image/UGB/UGBFINAL.jpg" alt="" /></div>
        <div class="flex w-11/12 flex-col justify-between">
          <p class="reveal mt-6 text-justify text-xs transition-opacity duration-500">
            The objective of the work I made was to transmit through art a critical eye towards the reign of the superficial in our society,
            more and more present with the emergence of social networks. This problem is indeed very present in our modern society where
            appearances are often more important than the intrinsic qualities of a person. To convey the message I wanted to approach a
            strong and powerful angle, so I chose to use symbolic visuals in the form of metaphor. The heart, made in an organic way,
            symbolizes the spirit and the depth of the person, while the head covered with a bandage evokes the idea that superficiality
            dominates the world and that we are more interested in appearances than in what really counts, the person behind it. This man is
            therefore obliged to put his heart out in an extreme way in order to prove his value as an "Ugly Boy".
          </p>
        </div>
      </div>
    </div>

    <!--VERSION Tablette -->
    <div class="hidden sm:block lg:hidden">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/UGB/UGBFINAL.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="reveal mt-6 text-justify text-xs opacity-100 duration-1000 lg:transition-opacity">
            The objective of the work I made was to transmit through art a critical eye towards the reign of the superficial in our society,
            more and more present with the emergence of social networks. This problem is indeed very present in our modern society where
            appearances are often more important than the intrinsic qualities of a person.
          </p>
          <h2 class="reveal cursor-pointer text-6xl font-bold tracking-tight">critical eye.</h2>
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/UGB/UGBFINAL.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="mt-6 text-justify text-xs opacity-100 duration-1000 lg:pr-36 lg:opacity-0 lg:transition-opacity" :id="descriptionId">
            The objective of the work I made was to transmit through art a critical eye towards the reign of the superficial in our society,
            more and more present with the emergence of social networks. This problem is indeed very present in our modern society where
            appearances are often more important than the intrinsic qualities of a person. To convey the message I wanted to approach a
            strong and powerful angle, so I chose to use symbolic visuals in the form of metaphor. The heart, made in an organic way,
            symbolizes the spirit and the depth of the person, while the head covered with a bandage evokes the idea that superficiality
            dominates the world and that we are more interested in appearances than in what really counts, the person behind it. This man is
            therefore obliged to put his heart out in an extreme way in order to prove his value as an "Ugly Boy".
          </p>
          <h2
            class="reveal animate-pulse cursor-pointer text-5xl font-bold tracking-tight opacity-0 hover:animate-none lg:text-8xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Critical eye.
          </h2>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block lg:hidden">
      <div class="mt-24 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/UGB/testpist.png" alt="" />
          <p class="reveal mt-6 w-1/2 px-3 text-justify text-xs duration-500">
            The choice of this strong imagery allows to capture the attention of the public and to invite reflection on the issue of
            superficiality. Indeed, the objective of this work was to transmit a message in the clearest possible way while trying to raise
            awareness among the public.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2 class="reveal w-1/2 cursor-pointer text-3xl font-bold tracking-tight sm:text-7xl">Superficiality.</h2>
          <img class="h-52 w-1/2 object-cover object-center" src="/public/image/UGB/ugbhead.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-40 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/UGB/testpist.png" alt="" />
          <p class="mt-6 w-1/2 pr-52 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId2">
            The choice of this strong imagery allows to capture the attention of the public and to invite reflection on the issue of
            superficiality. Indeed, the objective of this work was to transmit a message in the clearest possible way while trying to raise
            awareness among the public.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2
            class="reveal w-1/2 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-5xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Superficiality.
          </h2>
          <img class="h-52 w-1/2 object-cover object-center pr-32" src="/public/image/UGB/ugbhead.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="mx-auto w-11/12 items-center lg:hidden">
      <div class="mt-28 flex">
        <div class="w-1/2 pr-4">
          <h2 class="reveal h-1/3 pt-7 text-4xl font-bold tracking-tight sm:text-6xl">A message.</h2>
          <img class="mb-6 w-full object-cover" src="/public/image/UGB/head.png" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            Thus, by using painting as a means of artistic expression, I tried to address an important issue for our society.
          </p>
        </div>
        <div class="w-1/2 pl-4">
          <img class="mb-6 w-full object-cover" src="/public/image/UGB/hearth.png" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            The work is a strong message to encourage everyone to go beyond appearances and discover the depth of the human being.
          </p>
          <img class="mt-6 mb-6 w-full object-cover" src="/public/image/UGB/hand.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-52 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-0">
          <img class="h-60 w-1/3 object-cover" src="/public/image/UGB/head.png" alt="" />
          <p class="mt-6 w-1/3 px-12 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId3">
            Thus, by using painting as a means of artistic expression, I tried to address an important issue for our society.
          </p>
          <img class="h-60 w-1/3 object-cover object-top" src="/public/image/UGB/hearth.png" alt="" />
        </div>
        <div class="flex w-full flex-row-reverse items-end">
          <p class="w-1/3 pl-9 pb-6 pr-20 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId4">
            The work is a strong message to encourage everyone to go beyond appearances and discover the depth of the human being.
          </p>
          <img class="h-60 w-1/3 object-cover object-center" src="/public/image/UGB/hand.png" alt="" />
          <h2
            class="reveal w-1/3 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-6xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            A message.
          </h2>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Bouton from "../components/icons/Bouton.vue";
export default {
  name: "MyComponent",
  components: { Bouton },
  data() {
    return {
      descriptionId: "description-" + Math.random().toString(36).substring(7),
      descriptionId2: "description-" + Math.random().toString(36).substring(7),
      descriptionId3: "description-" + Math.random().toString(36).substring(7),
      descriptionId4: "description-" + Math.random().toString(36).substring(7),
      descriptionVisible: false,
    };
  },
  methods: {
    toggleDescription() {
      this.descriptionVisible = !this.descriptionVisible;
    },
    showDescription() {
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId);
        if (description) {
          description.style.opacity = "1";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId2);
        if (description) {
          description.style.opacity = "1";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId3);
        if (description) {
          description.style.opacity = "1";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId4);
        if (description) {
          description.style.opacity = "1";
        }
      }
    },
    hideDescription() {
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId);
        if (description) {
          description.style.opacity = "0";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId2);
        if (description) {
          description.style.opacity = "0";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId3);
        if (description) {
          description.style.opacity = "0";
        }
      }
      if (!this.descriptionVisible) {
        const description = document.getElementById(this.descriptionId4);
        if (description) {
          description.style.opacity = "0";
        }
      }
    },
    reveal() {
      var reveals = document.querySelectorAll(".reveal");

      for (var i = 0; i < reveals.length; i++) {
        var windowHeight = window.innerHeight;
        var elementTop = reveals[i].getBoundingClientRect().top;
        var elementVisible = 150;

        if (elementTop < windowHeight - elementVisible) {
          reveals[i].classList.add("active");
        } else {
          reveals[i].classList.remove("active");
        }
      }
    },
  },
  mounted() {
    window.addEventListener("scroll", this.reveal);
  },
  beforeDestroy() {
    window.removeEventListener("scroll", this.reveal);
  },
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  margin-top: 60px;
}
#description {
  display: none;
}
</style>

