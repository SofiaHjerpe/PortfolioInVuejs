<script setup>
import WelcomeItem from './WelcomeItem.vue'
</script>
<template>
  <WelcomeItem>
    <template #heading>
      <h3 class="heading" style="margin-bottom: 10px">Hi and welcome!</h3> 
      <p>My name is Sofia Hjerpe. Go to "About" to read more About me.</p>
    </template>
      <img class="image" src="../assets/me.jpg" />
  </WelcomeItem>
</template>