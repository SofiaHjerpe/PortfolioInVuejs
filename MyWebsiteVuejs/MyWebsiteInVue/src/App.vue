<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>
<template>
  <body>
    <nav>
      
      <div>
        <h1 class="logo">Sofia Hjerpe</h1>
         <p class="logo-line"> Junior Frontend developer and UX/UI designer</p>
     </div>
   
    
        <ul class="nav-links">
          <li><RouterLink to="/">Home</RouterLink></li>
          <li><RouterLink  to="/about">About</RouterLink></li>
          <li><RouterLink  to="/projects">Projects</RouterLink></li>
      </ul>  
<div class="burger">
  <div class="line1"></div>
  <div class="line2"></div>
  <div class="line3"></div>
</div>

</nav> 
 <div style="display:flex; justify-content: space-around">
  
  <router-view> 
  
  </router-view>
</div>
</body>
</template>

