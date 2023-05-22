<script>
import AppHeader from './components/AppHeader.vue'
import AppContent from './components/AppContent.vue'
import AppFooter from './components/AppFooter.vue'


export default{
  components:{
    AppHeader,
    AppContent,
    AppFooter,
  }
}
</script>

<template>
 <AppHeader />
 <AppContent />
 <AppFooter />
</template>

<style lang="scss">
 @use './assets/style/partials/_variables.scss' as *;
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

 .max-container{
   @include max-container
}
</style>