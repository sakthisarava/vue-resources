<template>
<the-header title="RememberMe"></the-header>
<the-resources></the-resources>
</template>

<script>
import TheHeader from './components/layout/TheHeader.vue';
import TheResources from './components/learning-resources/TheResources.vue';

export default {
    components: {
        TheHeader,
        TheResources
    },
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Josefin+Sans:wght@100;200;300;400;500;600;700&family=Lora:ital,wght@1,400;1,500&family=Poppins&family=Roboto:wght@500&family=Varela&family=Varela+Round&display=swap');

*{
    box-sizing: border-box;
}

html {
    font-family: 'Roboto', sans-serif;
}

body {
    margin: 0;
}
</style>