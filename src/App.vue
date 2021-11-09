<template>
    <div>
     <the-header title="RememberMe" />
    <the-resources></the-resources>
    </div>
</template>
<script>
import TheHeader from './components/layouts/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';
export default {
    components: { TheHeader, TheResources },
}
</script>
<style>
     @import url('https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;700&display=swap');

     * {
         box-sizing: border-box;
     }

     html {
         font-family: 'Prompt', sans-serif;
     }
     body {
         margin: 0;
     }
</style>