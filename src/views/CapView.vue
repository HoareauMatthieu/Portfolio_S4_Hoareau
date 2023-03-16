<template>
  <div class="mt-32 sm:ml-24 sm:mr-24">
    <div class="-mb-16 h-screen">
      <h1 class="mb-7 ml-6 text-4xl font-bold tracking-tight sm:ml-0 sm:text-7xl">Cap & Capuche</h1>
      <div class="h-4/6 bg-blue-400 sm:h-4/6">
        <img class="h-full w-full object-cover" src="/public/image/Cap/Cover.jpg" alt="" />
      </div>
      <div class="flex justify-between">
        <div class="animate__animated animate__fadeIn p-4 text-sm">
          <p>DEEMAX - CAP & CAPUCHE 02/2023</p>
        </div>
        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-center">Creation of the visual identity and artistic direction of the project</p>
        </div>
        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-right">COVER + MEDIA SUPPORT + ANIMATION CLIP</p>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block sm:hidden">
      <h2 class="reveal ml-6 text-7xl font-bold tracking-tight sm:text-9xl">Art direction.</h2>
      <div class="flex flex-col items-center">
        <div class="mt-3 w-9/12"><img class="object-cover" src="/public/image/Cap/Cover.jpg" alt="" /></div>
        <div class="flex w-11/12 flex-col justify-between">
          <p class="reveal mt-6 text-justify text-xs transition-opacity duration-500">
            For the release of the first project of the promising Parisian rapper Deemax, I was in charge of the entire art direction of the
            project. The goal was to create a strong imagery, reminding the old school aspect of Deemax's music, while being a subtle
            reminder of the subject : "cap & hood". The starting point was to focus on the center of the project: the cover. It was
            necessary to determine the most effective composition for the cover, conveying the most emotion. I went for a contrast between
            the black representing Deemax and his team and an off-white allowing to add depth to the black, visual lightness, while
            recalling an old school aspect desired via the texture.
          </p>
        </div>
      </div>
    </div>

    <!--VERSION Tablette -->
    <div class="hidden sm:block lg:hidden">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Cap/Cover.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="reveal mt-6 text-justify text-xs opacity-100 duration-1000 lg:transition-opacity">
            For the release of the first project of the promising Parisian rapper Deemax, I was in charge of the entire art direction of the
            project. The goal was to create a strong imagery, reminding the old school aspect of Deemax's music, while being a subtle
            reminder of the subject : "cap & hood".
          </p>
          <h2 class="reveal cursor-pointer text-6xl font-bold tracking-tight">Art direction.</h2>
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Cap/Cover.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="mt-6 text-justify text-xs opacity-100 duration-1000 lg:pr-36 lg:opacity-0 lg:transition-opacity" :id="descriptionId">
            For the release of the first project of the promising Parisian rapper Deemax, I was in charge of the entire art direction of the
            project. The goal was to create a strong imagery, reminding the old school aspect of Deemax's music, while being a subtle
            reminder of the subject : "cap & hood". The starting point was to focus on the center of the project: the cover. It was
            necessary to determine the most effective composition for the cover, conveying the most emotion. I went for a contrast between
            the black representing Deemax and his team and an off-white allowing to add depth to the black, visual lightness, while
            recalling an old school aspect desired via the texture.
          </p>
          <h2
            class="reveal animate-pulse cursor-pointer text-5xl font-bold tracking-tight opacity-0 hover:animate-none lg:text-9xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Art direction.
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

