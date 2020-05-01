<template lang="pug">
  div
    h1 Home
</template>

<script lang="ts">
import { Component, Prop, Vue } from 'vue-property-decorator'

@Component
export default class Home extends Vue {
  @Prop() private msg!: string
}
</script>
