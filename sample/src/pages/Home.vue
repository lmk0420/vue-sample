<template>
  <div class="home">
    <SampleTable />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import SampleTable from "@/components/SampleTable.vue";

@Component({
  components: {
    SampleTable
  }
})
export default class Home extends Vue {}
</script>
