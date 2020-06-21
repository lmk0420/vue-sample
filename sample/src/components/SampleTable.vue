<template>
  <v-data-table
    :headers="headers"
    :items="items"
  >
  </v-data-table>  
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import { Header } from '../types/types'

@Component
export default class SampleTable extends Vue {
  get headers(): Header[] {
    return [{
      text: "test1",
      value: "test1"
    },
    {
      text: "test2",
      value: "test2"
    },{
      text: "test3",
      value: "test3"
    },
    {
      text: "test4",
      value: "test4"
    }]
  }

  get items() {
    return [{
      test1: "hoge",
      test2: "fuga",
      test3: "hogehoge",
      test4: "fugafuga"
    }]
  }

}
</script>
