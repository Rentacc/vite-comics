<script>
import AppHeader from './components/AppHeader.vue';
 //const AppHeader = valore esportato dal file importato
 import AppFooter from './components/AppFooter.vue';
 import AppContent from './components/AppContent.vue';
 
export default{
  components: {
    AppHeader,
    AppFooter,
    AppContent,
   
  },

};

</script>

<template>
<app-header></app-header>
<AppContent></AppContent>
<AppFooter></AppFooter>
</template>

<style scoped>

</style>
