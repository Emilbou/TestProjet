<template>
  <h1 class="text-white text-2xl p-2 text-center bg-black">Tp 01</h1>
  <section class="px-8">
    <h2 class="text-black text-1x1 p-1 text-left">Couleurs :</h2>
    <div class="flex">
      <bouton class="rounded-l-xl bg-Marron1"></bouton>
      <bouton class="bg-marron2"></bouton>
      <bouton class="bg-marron3"></bouton>
      <bouton class="rounded-b-xl bg-marron4"></bouton>
    </div>
    <div class="flex my-2">
      <bouton class="bg-noir"></bouton>
      <bouton class="bg-darkmarron"></bouton>
      <bouton class="bg-jesaispas"></bouton>
      <bouton class="bg-jaunepale"></bouton>
    </div>
    <h2 class="text-black font-roboto font-bold">Test</h2>
    <ArchiveIcon class="w-10" />
  </section>
</template>
<script >
import Bouton from "./components/Bouton.vue";
import { ArchiveIcon } from "@heroicons/vue/outline";
export default {
  name: "App",
  components: { Bouton, ArchiveIcon },
};
</script>