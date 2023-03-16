<template>
  <div class="mt-32 sm:ml-24 sm:mr-24">
    <div class="-mb-16 h-screen">
      <h1 class="mb-7 ml-6 text-4xl font-bold tracking-tight sm:ml-0 sm:text-7xl">Bleu</h1>
      <div class="h-4/6 bg-blue-400 sm:h-4/6">
        <img class="h-full w-full object-cover" src="/public/image/Bleu/clip1.png" alt="" />
      </div>
      <div class="flex justify-between">
        <div class="animate__animated animate__fadeIn p-4 text-sm">
          <p>BLEU - LAPOSTROZ 02/2023</p>
        </div>
        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-center">
            Creation of the visual identity and co-production of the artistic direction of the project
          </p>
        </div>
        <div class="p-4 text-sm">
          <p class="animate__animated animate__fadeIn text-right">COVER + DA + GRAPHIC CREATION OF THE CLIP</p>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block sm:hidden">
      <h2 class="reveal ml-6 text-7xl font-bold tracking-tight sm:text-9xl">Blue vision.</h2>
      <div class="flex flex-col items-center">
        <div class="mt-3 w-9/12"><img class="object-cover" src="/public/image/Bleu/Cover.jpg" alt="" /></div>
        <div class="flex w-11/12 flex-col justify-between">
          <p class="reveal mt-6 text-justify text-xs transition-opacity duration-500">
            After the release of his EP Rouge in May 2022, Lapostroz, a young artist from Nice based in the Capital, released 2 singles for
            which I made the visuals. After one year of waiting, he finally came back in March 2022 with the sequel of his first Volume
            entitled BLEU. I was in charge of the visual aspect and the artistic direction of the cover. We decided to prolong the style and
            the vision established in his first project ROUGE. More introspective, we decided via the color BLUE to represent this time
            Lapostroz himself on the cover in order to stick with the theme and the subjects treated in the project. The style, although
            similar, has been purified and the lines are more precise, allowing to produce a project with an even more efficient visual (and
            as a proof of my progression as an artist). Also wanting to make a reminder to his hometown, the blue at the origin of this
            production is Klein blue, created by the artist Yves Klein from Nice who painted his city with it.
          </p>
        </div>
      </div>
    </div>

    <!--VERSION Tablette -->
    <div class="hidden sm:block lg:hidden">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Bleu/Cover.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="reveal mt-6 text-justify text-xs opacity-100 duration-1000 lg:transition-opacity">
            After the release of his EP Rouge in May 2022, Lapostroz, a young artist from Nice based in the Capital, released 2 singles for
            which I made the visuals. After one year of waiting, he finally came back in March 2022 with the sequel of his first Volume
            entitled BLEU. I was in charge of the visual aspect and the artistic direction of the cover. We decided to prolong the style and
            the vision established in his first project ROUGE.
          </p>
          <h2 class="reveal cursor-pointer text-6xl font-bold tracking-tight">Blue vision.</h2>
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="flex gap-5">
        <div class="w-2/3 lg:w-1/2"><img class="object-cover lg:w-3/4" src="/public/image/Bleu/Cover.jpg" alt="" /></div>
        <div class="flex w-1/3 flex-col justify-between lg:w-1/2">
          <p class="mt-6 text-justify text-xs opacity-100 duration-1000 lg:pr-32 lg:opacity-0 lg:transition-opacity" :id="descriptionId">
            After the release of his EP Rouge in May 2022, Lapostroz, a young artist from Nice based in the Capital, released 2 singles for
            which I made the visuals. After one year of waiting, he finally came back in March 2022 with the sequel of his first Volume
            entitled BLEU. I was in charge of the visual aspect and the artistic direction of the cover. We decided to prolong the style and
            the vision established in his first project ROUGE. More introspective, we decided via the color BLUE to represent this time
            Lapostroz himself on the cover in order to stick with the theme and the subjects treated in the project. The style, although
            similar, has been purified and the lines are more precise, allowing to produce a project with an even more efficient visual (and
            as a proof of my progression as an artist). Also wanting to make a reminder to his hometown, the blue at the origin of this
            production is Klein blue, created by the artist Yves Klein from Nice who painted his city with it.
          </p>
          <h2
            class="reveal animate-pulse cursor-pointer text-5xl font-bold tracking-tight opacity-0 hover:animate-none lg:text-9xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Blue vision.
          </h2>
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="block lg:hidden">
      <div class="mt-24 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/Bleu/titre.png" alt="" />
          <p class="reveal mt-6 w-1/2 px-3 text-justify text-xs duration-500">
            I also recreated a typography similar to the one on Rouge to keep a very similar design and style, linking the two projects.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2 class="reveal w-1/2 cursor-pointer text-3xl font-bold tracking-tight sm:text-7xl">Titling.</h2>
          <img class="h-52 w-1/2 object-cover object-center" src="/public/image/Bleu/Tracklist.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-40 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-6">
          <img class="h-52 w-1/2 object-cover" src="/public/image/Bleu/titre.png" alt="" />
          <p class="mt-6 w-1/2 pr-52 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId2">
            I also recreated a typography similar to the one on Rouge to keep a very similar design and style, linking the two projects.
          </p>
        </div>
        <div class="flex w-full flex-row-reverse items-end gap-6">
          <h2
            class="reveal w-1/2 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-9xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Titling.
          </h2>
          <img class="h-52 w-1/2 object-cover object-center pr-32" src="/public/image/Bleu/Tracklist.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION MOBILE -->
    <div class="mx-auto w-11/12 items-center lg:hidden">
      <div class="mt-28 flex">
        <div class="w-1/2 pr-4">
          <h2 class="reveal h-1/3 pt-7 text-4xl font-bold tracking-tight sm:text-6xl">Clip creation.</h2>
          <img class="mb-6 w-full object-cover" src="/public/image/Bleu/clip3.png" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            Supervised by the Artistic Direction of the Director Matthieu Allard, I also had the mission to perpetuate this coherence of
            artistic vision between the cover of the project and the video clip of the title BLEU, which was released two weeks before the
            EP (allowing to make the trailer).
          </p>
        </div>
        <div class="w-1/2 pl-4">
          <img class="mb-6 w-full object-cover" src="/public/image/Bleu/clip2.png" alt="" />
          <p class="reveal w-full text-justify text-xs duration-500">
            On this project the objective was to realize coherent and effective animation with the universe of the artist while producing a
            content adapting to the clip directed by Matthieu Allard. The whole in a lapse of time very reduced by the deadlines imposed.
          </p>
          <img class="mt-6 mb-6 w-full object-cover" src="/public/image/Bleu/cliprond.png" alt="" />
        </div>
      </div>
    </div>

    <!--VERSION PC -->
    <div class="hidden lg:block">
      <div class="mt-52 flex flex-col">
        <div class="flex w-full flex-row-reverse items-center gap-0">
          <img class="h-60 w-1/3 object-cover" src="/public/image/Bleu/clip2.png" alt="" />
          <p class="mt-6 w-1/3 px-12 pl-9 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId3">
            Supervised by the Artistic Direction of the Director Matthieu Allard, I also had the mission to perpetuate this coherence of
            artistic vision between the cover of the project and the video clip of the title BLEU, which was released two weeks before the
            EP (allowing to make the trailer).
          </p>
          <img class="h-60 w-1/3 object-cover object-top" src="/public/image/Bleu/clip3.png" alt="" />
        </div>
        <div class="flex w-full flex-row-reverse items-end">
          <p class="w-1/3 pl-9 pb-6 pr-20 text-justify text-xs opacity-0 transition-opacity duration-500" :id="descriptionId4">
            On this project the objective was to realize coherent and effective animation with the universe of the artist while producing a
            content adapting to the clip directed by Matthieu Allard. The whole in a lapse of time very reduced by the deadlines imposed.
          </p>
          <img class="h-60 w-1/3 object-cover object-center" src="/public/image/Bleu/cliprond.png" alt="" />
          <h2
            class="reveal w-1/3 animate-pulse cursor-pointer text-3xl font-bold tracking-tight opacity-0 hover:animate-none sm:text-7xl"
            @click="toggleDescription"
            @mouseover="showDescription"
            @mouseout="hideDescription"
          >
            Clip creation.
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

