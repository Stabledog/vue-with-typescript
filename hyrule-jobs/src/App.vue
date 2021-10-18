<template>
    <div class="app">
        <p>{{name}}</p>
        <button @click="changeName('zelda')">Change Name</button>
    </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';

export default defineComponent({
  name: 'App',
  components: {
  },
  data() {
      return {
          name: 'Foo hybrid'
          };
      },
  methods: {
      changeName(name:string) {
          this.name=name;
          }
      }

});
</script>

<style>
</style>
