<script setup>
const buildId = import.meta.env.VITE_BUILD_ID ?? 'local'
const today = new Date().toLocaleDateString('fr-FR')
</script>
<template>
  <header>
    <p>Nom : Noé Loisel</p>
    <p>Date : {{ today }}</p>
    <p>Build : {{ buildId }}</p>
    <p>Test modif 2 galère</p>
  </header>
</template>