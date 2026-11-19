<script>
  //To be able to add a component into another component, in the script block, import the component
  //The name of the component is the name of the file by default.
  // Add export default {} to be able to add imported component in the root component
  import NavbarComponent from './components/NavbarComponent.vue';
  import HomePage from './pages/HomePage.vue';
  import CoursesPage from './pages/CoursesPage.vue';

  export default {
    components: {
      NavbarComponent,
      HomePage,
      CoursesPage
    }
  }
</script>

<template>
  <NavbarComponent />
  <HomePage />
  <CoursesPage />
</template>

<style scoped>

</style>