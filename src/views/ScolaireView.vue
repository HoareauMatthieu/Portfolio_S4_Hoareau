<template>
  <div class="relative flex w-full overflow-hidden pt-16">
    <span class="scrolltxt whitespace-nowrap text-6xl font-semibold uppercase">School Work school work&nbsp;</span>
    <span class="scrolltxt whitespace-nowrap text-6xl font-semibold uppercase">School Work school work&nbsp;</span>
  </div>

  <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3">
    <div class="relative row-span-2 h-full bg-blue-400">
      <router-link to="/cap">
        <img src="/public/image/Cap/Cover.jpg" alt="" class="h-full w-full object-cover" />
        <div
          class="absolute top-0 left-0 flex h-full w-full items-center justify-center bg-black bg-opacity-50 opacity-0 hover:opacity-100"
        >
          <h2 class="text-center text-xs uppercase text-white">
            DEEMAX CAP & CAPUCHE <br />
            2023
          </h2>
        </div>
      </router-link>
    </div>

    <div class="relative w-full bg-blue-200">
      <router-link to="/bleu">
        <img src="/public/image/Bleu/Cover.jpg" alt="" class="object-cover" />
        <div
          class="absolute top-0 left-0 flex h-full w-full items-center justify-center bg-black bg-opacity-50 opacity-0 hover:opacity-100"
        >
          <h2 class="text-xs uppercase text-white">BLEU <br />2023</h2>
        </div>
      </router-link>
    </div>
    <div class="relative w-full bg-blue-400">
      <img src="/public/image/Cap/Cover.jpg" alt="" class="h-full w-full object-cover" />
      <div class="absolute top-0 left-0 flex h-full w-full items-center justify-center bg-black bg-opacity-50 opacity-0 hover:opacity-100">
        <h2 class="text-xl uppercase text-white">Votre texte ici</h2>
      </div>
    </div>
    <div class="relative col-span-2 h-60 w-full bg-blue-500">
      <img src="/public/image/Rouge/cover.jpeg" alt="" class="h-full w-full object-cover object-center" />
      <div class="absolute top-0 left-0 flex h-full w-full items-center justify-center bg-black bg-opacity-50 opacity-0 hover:opacity-100">
        <h2 class="text-xl uppercase text-white">Votre texte ici</h2>
      </div>
    </div>
  </div>
</template>
