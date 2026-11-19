<!-- Script: A block of JavaScript code that defines the behavior and logic of the component -->
<script>
  //To be able to add a component into another component, in the script block, import the component
  //The name of the component is the name of the file by default.
  // Add export default {} to be able to add imported component in the root component
    import BannerComponent from './components/BannerComponent.vue';
    import NavbarComponent from './components/NavbarComponent.vue';
    import CoursesPage from './pages/CoursesPage.vue';

    export default {
      components: {
        BannerComponent,
        NavbarComponent,
        CoursesPage
      }
    }
</script>

<template>
  <NavbarComponent />
  <CoursesPage />
  <BannerComponent />

</template>

<style scoped>

</style>