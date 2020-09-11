<template>
  <div>
      <p>hello</p>
      {{val}}
  </div>
</template>

<script>
import Vue from 'vue'
import Component from 'vue-class-component'


@Component
export default class App extends Vue {
    val = 'hhh'
    mounted(){
        console.log(this.val)
    }
}
</script>

<style>

</style>