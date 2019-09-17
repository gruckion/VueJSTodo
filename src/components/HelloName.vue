<template>
  <div class="hello">
    Hello {{ name }}
  </div>
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class HelloName extends Vue {
    @Prop() private name!: string;
}
</script>
