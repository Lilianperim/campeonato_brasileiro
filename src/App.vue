<template>
  <v-app>
  <AppTopBar></AppTopBar>
  
    <v-main>
    <Inicio></Inicio>
    </v-main>
  </v-app>
</template>

<script>
import Inicio from './components/Inicio'
import AppTopBar from './components/shared/AppTopBar'

export default {
  name: 'App',
  components:{
      Inicio,
      AppTopBar
  },
 
};
</script>
