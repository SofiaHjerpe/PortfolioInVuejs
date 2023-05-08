<script setup>
import ProjectComponent from '../components/ProjectComponent.vue'
import ImageItem from '../components/ImageItem.vue'

</script>
<template>
  <div class="project-container">
   
      <h1 class="heading" style="margin-inline:0">Projects</h1>
      <div class="projects">
      <ProjectComponent :heading ="'Recipe App'" description= "I made a Recipe app in C# .NET MVC. The Recipe app consists of a list of recipes. The recipe has a title, summary and an image. If you click on details you come to a seperate page where you can take a closer look at the recipe. 
      I also have a seperate console app where the user can add more recipes to the Recipe app." :link="'https://github.com/SofiaHjerpe/RecipeApp1'" :languages = "[ 'C# .Net MVC'] ">

        <template #list>
        </template>
      </ProjectComponent>
      <ImageItem :projectImages="['./src/assets/Recipe1.JPG', './src/assets/Recipe2.JPG' ]"><template #images></template></ImageItem>
     </div>
 
      <div class="projects">

      <ProjectComponent :heading ="'Company Page'" description= "I made a website for a company that I named Traning.nu. The website includes a map and a form. 
      When I made the website I used programs and programming languages such as C # .NET MVC, C# Console App,CSS and Visual Studio 2022. For the design I used a lighter pink. For the design I used a lighter green color on buttons. 
      I used the default C# and .NET MVC template. I used a light hovering color on links and buttons." :link="'https://github.com/SofiaHjerpe/Traning.nu'" :languages= "[ 'C# .Net MVC','C# Console App','CSS' , 'Javascript'] ">

       <template #list>    
       </template>
      </ProjectComponent>
      <ImageItem  :projectImages="['./src/assets/Traning.nu1.jpg', './src/assets/Traning.nu2.jpg', './src/assets/Traning.nu5.JPG', './src/assets/Traning.nu4.JPG' ]"> <template #images></template></ImageItem>
      </div>
      <div class="projects">

      <ProjectComponent :heading ="'Training app'" description= "I made a Training app. Here the user can create an exercise. The user can then go to Training history to tell how the training went." :link="'https://github.com/SofiaHjerpe/Training'" :languages= "['C# .Net MVC'] ">

       <template #list>    
       </template>
      </ProjectComponent>
      <ImageItem :projectImages="['./src/assets/trainingapp1.jpg', './src/assets/trainingapp2.jpg', './src/assets/trainingapp3.jpg'  , './src/assets/trainingapp4.jpg' ]"> <template #images></template></ImageItem>
      </div>
      <div class="projects">

      <ProjectComponent :heading ="'Tic tac toe'" description= "I made a Tic tac toe game. First the player X is moving by typing in row 0-2 and column 0-2. Then player O is moving by typing in row and column. The first player that gets 3 O's or X's in a row wins the game. For now the players can only win one way, but I will update so that the users have more ways to win." :link="'https://github.com/SofiaHjerpe/Tictactoe'" :languages= "['C# .Net Console App'] ">

       <template #list>    
       </template>
      </ProjectComponent>
      <ImageItem :projectImages="['./src/assets/Tictactoe1.jpg', './src/assets/Tictactoe2.jpg']"><template #images></template></ImageItem>
     </div>
     <div class="projects">

     <ProjectComponent :heading ="'My Relatives Website'" description= "During my studies I made a website to my Uncle that is an Music writer and an Illustrator. I made a web shop for his artwork. When I made the website I followed the Design Thinking process. The Design Thinking process has 5 phases. The 5 phases are; The empathy phase, the define phase, the idea generation phase, the prototype phase and the iteration phase. When building the website I for example used the prototyping phase to make a Hifi-prototype in Figma. " :link="'https://magnushjerpe.com/produkt/sleighride/'" :languages= "['Wordpress', 'Elementor', 'WooCommerce', 'Figma', 'CSS' ] ">

      <template #list>    
      </template>
     </ProjectComponent>
     <ImageItem :projectImages="['./src/assets/MH.jpg', './src/assets/MH1.jpg', './src/assets/MH2.jpg', './src/assets/MH3.jpg' ]"><template #images></template></ImageItem>
     </div>
 </div>
</template>

 