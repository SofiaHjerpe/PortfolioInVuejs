<script setup>

const props = defineProps({
  projectImages: {
    type: Array,
    required: true
  }
});

</script>
<template>  
            <div class="image-item">
                <slot name="images"> 
                <img style="max-width: 300px; border-radius: 4px" :src="projectImages[0]" />
                <img style="max-width: 300px; border-radius: 4px" :src="projectImages[1]"  />
                <img style="max-width: 300px; border-radius: 4px" :src="[projectImages[2]]"  />
                <img style="max-width: 300px; border-radius: 4px" :src="[projectImages[3]]"  />
                <img style="max-width: 300px; border-radius: 4px" :src="[projectImages[4]]" /> 
                </slot>

            </div>
</template>

