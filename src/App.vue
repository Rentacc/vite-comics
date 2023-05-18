<script>
import AppHeader from './components/AppHeader.vue';
 //const AppHeader = valore esportato dal file importato
 import AppFooter from './components/AppFooter.vue';
 import AppContent from './components/AppContent.vue';
 import AppContent2 from './components/AppContent2.vue';
 import AppContent3 from './components/AppContent3.vue';
export default{
  components: {
    AppHeader,
    AppFooter,
    AppContent,
    AppContent2,
    AppContent3,
  },

};

</script>

<template>
<app-header></app-header>
<AppContent></AppContent>
<AppContent2></AppContent2>
<AppContent3></AppContent3>
<AppFooter></AppFooter>
</template>

<style scoped>

</style>
