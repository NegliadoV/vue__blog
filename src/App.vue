<script setup>
import Navigation from "./components/Navigation.vue";
import Common from "./components/Common.vue";
import Posts from "./components/Posts.vue";
import PushBtn from "./components/PushBtn.vue";
import CreatePost from './components/CreatePost.vue';

</script>

<template>
  <CreatePost />
  <div class="container">
    <Navigation />
    <Common />
    <Posts /> 
    <PushBtn /> 
  </div>
</template>

<style scoped>

</style>
