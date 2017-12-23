<template>
  <div class="hello">{{ msg }}</div>
</template>

<script lang="ts">
import Vue from 'vue'
import Component from 'vue-class-component'

@Component({
  name: 'Hello'
})
export default class Hello extends Vue {
  msg = 'Hello, world'
}
</script>
