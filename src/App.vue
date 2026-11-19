<script>
  
  import NavbarComponent from './components/NavbarComponent.vue';
  import HomePage from './pages/HomePage.vue';
  import HighlightsComponent from './components/HighlightsComponent.vue';
  import CourseComponent from './components/CourseComponent.vue';
  import CourseComponent2 from './components/CourseComponent2.vue';
  import CourseComponent3 from './components/CourseComponent3.vue';

  export default {
    components: {
      NavbarComponent, HomePage, HighlightsComponent, CourseComponent, CourseComponent2, CourseComponent3
    }
  }
</script>

<template>
  <NavbarComponent />
  <HomePage />
</template>

<style scoped>

</style>