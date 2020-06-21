<template>
  <v-app>
    <div>
      <Home />
    </div>
  </v-app>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Home from './components/SampleTable.vue'

@Component({
  components: {
    Home
  }
})
export default class App extends Vue{}
</script>
