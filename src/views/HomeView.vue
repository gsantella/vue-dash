<script setup>
import TheWelcome from "@/components/TheWelcome.vue";
import Hero from "@/components/Hero.vue";
import InfoTiles from "@/components/InfoTiles.vue";
import Columns from "@/components/Columns.vue";
import ApiMocky from "@/components/ApiMocky.vue";
import ApiCloudFlare from "@/components/ApiCloudFlare.vue";
import ApiReplit from "@/components/ApiReplit.vue";
</script>

<template>
  <main>
    <Hero />
    <h1>Vercel Test Change</h1>
    <ApiReplit />
    <InfoTiles />
    <Columns />
  </main>
</template>
