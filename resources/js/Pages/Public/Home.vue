<template>
    <Hero :projectName="'Dashboard'" :projectDescription="'An Open source(MIT) Dashboard kit built with VILT Stack.'"
        :whatsNewText="'New LMS Project Available in LaraVueTail'" :whatsNewLink="'https://laravuetail.com/'"
        :projectGitRepoLink="'https://github.com/LaraVueTail/dashboard-laravel-vue-tailwind-inertia-VILT-Stack'">
    </Hero>
    <WatchVideoVue></WatchVideoVue>
    <WhatIsThis></WhatIsThis>
    <!-- <Posts :noColumn="2" :heading="'Blog Posts'" :subHeading="'Checkout our sample posts.'" :posts="posts"></Posts> -->
</template>
<script>
export default {
    props: ["posts"],
};
</script>
<script setup>
import Hero from "../../Shared/HomePageContents/Hero.vue";
import WatchVideoVue from '../../Shared/HomePageContents/WatchVideo.vue';
import WhatIsThis from "../../Shared/HomePageContents/WhatIsThis.vue";
// import Posts from "./Posts/Index.vue";
</script>
