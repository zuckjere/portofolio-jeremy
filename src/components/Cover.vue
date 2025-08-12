<script setup>
import Bouton from "./Bouton.vue";
</script>
<template>
  <div class="w-full h-screen flex flex-col bg-green-500 space-y-8">
    <h1 class="text-4xl font-bold mt-32 text-center font-sans">
      Vous cherchez un développeur web?
    </h1>
    <p class="mt-4 text-lg text-center max-w-3xl px-4 mx-auto">
      Passionné par le développement web, je conçois et développe des sites et
      applications performants en combinant design soigné et technologies
      modernes. Mon objectif : créer des expériences digitales intuitives qui
      répondent parfaitement aux besoins des utilisateurs.
    </p>
    <Bouton label="Contactez-moi" />
  </div>
</template>
