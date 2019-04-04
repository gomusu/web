<template>
  <v-app>
<!--    <v-toolbar app>
      <v-toolbar-title class="headline text-uppercase pointer" @click="onTitleClick">
      <img
        class="mr-2"
        :src="require('./assets/logo.png')"
        height="16px"
      />
        <span>Gomusu</span>
      </v-toolbar-title>
      <v-spacer></v-spacer>
    </v-toolbar>-->

    <v-content class="content">
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
  },
  methods: {
    onTitleClick() {
      window.location = window.location.origin + '/';
    }
  }
}
</script>

<style>
.pointer {cursor: pointer;}

.content {
  min-height: 100vh;
  background-color: black;
  background-image: url('./assets/header.png');
  background-size: 100%;
  background-repeat: no-repeat;
  color: white;
}

</style>
