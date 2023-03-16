<template>
  <div class="mt-32 sm:ml-24 sm:mr-24">
    <div class="-mb-16 h-screen">
      <h1 class="mb-7 ml-6 text-4xl font-bold tracking-tight sm:ml-0 sm:text-7xl">Moments + 1000</h1>
      <div class="h-4/6 bg-blue-400 sm:h-4/6">
        <img class="h-full w-full object-cover" src="/public/image/Deemax/Water.jpg" alt="" />
      </div>
      <div class="flex justify-between">
        <div class="animate__animated animate__fadeIn p-4 text-sm">
          <p>DEEMAX - Moments + 1000</p>
        </div>

        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-right">02/2023</p>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block sm:hidden">
      <h2 class="reveal ml-6 text-7xl font-bold tracking-tight sm:text-9xl">Feelings.</h2>
      <div class="flex flex-col items-center">
        <div class="mt-3 w-9/12"><img class="object-cover" src="/public/image/Deemax/Water.jpg" alt="" /></div>
        <div class="flex w-11/12 flex-col justify-between">
          <p class="reveal mt-6 text-justify text-xs transition-opacity duration-500">
            I had the opportunity to create the visuals for the double single of the rapper DeeMax in collaboration with his beatmaker
            Poivre Blanc. The main goal of this illustration was to represent the main theme of the project, through the psychological state
            of the man who is trapped in the abyss. To do so, I used a visual metaphor of the man immersed in the depths of the ocean, which
            symbolizes his emotional depth and isolation.
          </p>
        </div>
      </div>
    </div>

    <!--VERSION Tablette -->
    <div class="hidden sm:block lg:hidden">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Deemax/Water.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="reveal mt-6 text-justify text-xs opacity-100 duration-1000 lg:transition-opacity">
            I had the opportunity to create the visuals for the double single of the rapper DeeMax in collaboration with his beatmaker
            Poivre Blanc. The main goal of this illustration was to represent the main theme of the project, through the psychological state
            of the man who is trapped in the abyss.
          </p>
          <h2 class="reveal cursor-pointer text-6xl font-bold tracking-tight">Feelings.</h2>
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Deemax/Water.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="mt-6 text-justify text-xs opacity-100 duration-1000 lg:pr-36 lg:opacity-0 lg:transition-opacity" :id="descriptionId">
            I had the opportunity to create the visuals for the double single of the rapper DeeMax in collaboration with his beatmaker
            Poivre Blanc. The main goal of this illustration was to represent the main theme of the project, through the psychological state
            of the man who is trapped in the abyss. To do so, I used a visual metaphor of the man immersed in the depths of the ocean, which
            symbolizes his emotional depth and isolation.
          </p>
          <h2
            class="reveal animate-pulse cursor-pointer text-5xl font-bold tracking-tight opacity-0 hover:animate-none lg:text-9xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Feelings.
          </h2>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block lg:hidden">
      <div class="mt-24 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/Cap/MédiaDeemax.jpg" alt="" />
          <p class="reveal mt-6 w-1/2 px-3 text-justify text-xs duration-500">
            The project required a lot of work and some of the interesting proposals that did not fit into the framework of an album cover
            (lacking visual imact) were reused for the interviews with the media.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2 class="reveal w-1/2 cursor-pointer text-3xl font-bold tracking-tight sm:text-7xl">Media visual.</h2>
          <img class="h-52 w-1/2 object-cover object-center" src="/public/image/Cap/DEEV8.jpg" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-40 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/Cap/MédiaDeemax.jpg" alt="" />
          <p class="mt-6 w-1/2 pr-52 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId2">
            The project required a lot of work and some of the interesting proposals that did not fit into the framework of an album cover
            (lacking visual imact) were reused for the interviews with the media.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2
            class="reveal w-1/2 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-5xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Media visual.
          </h2>
          <img class="h-52 w-1/2 object-cover object-center pr-32" src="/public/image/Cap/DEEV8.jpg" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="mx-auto w-11/12 items-center lg:hidden">
      <div class="mt-28 flex">
        <div class="w-1/2 pr-4">
          <h2 class="reveal h-1/3 pt-7 text-4xl font-bold tracking-tight sm:text-6xl">Project extensions.</h2>
          <img class="mb-6 w-full object-cover" src="/public/image/Cap/Tracklist.jpg" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            I also took care of the Tracklist which is an extension of the cover with the graphic style of the latter. The whole was
            realized in order to conceive soon physical CD of the project.
          </p>
        </div>
        <div class="w-1/2 pl-4">
          <img class="mb-6 w-full object-cover" src="/public/image/Cap/DEEM.jpg" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            The artistic direction of the album was also accompanied by a visual clip animated by me, which was released on my own accounts
            for reasons of timing. The clip which I directed the scenario, the editing, as well as the illustrations had for goal to take
            again this artistic direction contrasting the black and white in a slightly different style to evoke the topic of the project
            under a similar angle, but which is not repetitive.
          </p>
          <img class="mt-6 mb-6 w-full object-cover" src="/public/image/Cap/DEEANIM.jpg" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-52 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-0">
          <img class="h-60 w-1/3 object-cover" src="/public/image/Cap/DEEM.jpg" alt="" />
          <p class="mt-6 w-1/3 px-12 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId3">
            I also took care of the Tracklist which is an extension of the cover with the graphic style of the latter. The whole was
            realized in order to conceive soon physical CD of the project.
          </p>
          <img class="h-60 w-1/3 object-cover object-top" src="/public/image/Cap/Tracklist.jpg" alt="" />
        </div>
        <div class="flex w-full flex-row-reverse items-end">
          <p class="w-1/3 pl-9 pb-6 pr-20 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId4">
            The artistic direction of the album was also accompanied by a visual clip animated by me, which was released on my own accounts
            for reasons of timing. The clip which I directed the scenario, the editing, as well as the illustrations had for goal to take
            again this artistic direction contrasting the black and white in a slightly different style to evoke the topic of the project
            under a similar angle, but which is not repetitive.
          </p>
          <img class="h-60 w-1/3 object-cover object-center" src="/public/image/Cap/DEEANIM.jpg" alt="" />
          <h2
            class="reveal w-1/3 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-6xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Project extensions.
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

