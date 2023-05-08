<script setup>
const props = defineProps({
  description: String, 
  link: String,
  heading: String,
  languages: {
    type: Array,
    required: true
  }
});
</script>
<template>
    <div class="project-item">
        <h4 class="project-heading" >{{ heading }} </h4>
           <p class="project-description">{{ description }}</p> 
           <span class="project-link">Link: <a style="overflow: hidden;text-overflow: ellipsis; ">{{ link }}</a></span>
        
           <div>
            <slot name="list">
                <span class="list-wrap">Languages:  <div class="list-of-languages">
                    {{ languages }}
                </div></span>
               
            </slot>
        </div>
    </div>
    
</template>
