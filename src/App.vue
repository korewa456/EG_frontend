<template>
  <v-app>
    <Alert/>
    <Toolbar/>
    <Sidebar></Sidebar>
    <v-content>
      <router-view/>
    </v-content>
  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import Alert from './components/alert_component'
import Toolbar from './components/toolbar'
import Sidebar from './components/NavigationDrawer'
export default {
  name: 'App',
  components: {
    HelloWorld,
    Alert,
    Toolbar,
    Sidebar
  },
  data () {
    return {
      //
    }
  }
}
</script>
