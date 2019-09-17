<template>
  <div class="home">
    <HelloName name="Stephen!" />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import HelloName from '@/components/HelloName.vue'

@Component({
  components: {
    HelloName
  }
})
export default class Home extends Vue {}
</script>
