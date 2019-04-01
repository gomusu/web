<template>
  <v-app>
    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase">
      <img
        :src="require('./assets/logo.png')"
        height="16px"
      />
        <span>Gomusu</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>

    <v-content>
      <Contributor/>
    </v-content>
  </v-app>
</template>

<script>
import Contributor from './components/Contributor'

export default {
  name: 'App',
  components: {
    Contributor
  },
  data () {
    return {
      //
    }
  }
}
</script>
