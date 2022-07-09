<template>
  <div>
    <h1 @click="clicked">Hello</h1>
  </div>
</template>

<script lang="ts">
import { TestObj } from "@/interfaces/testObj";

export default {
  name: "HomeView",

  methods: {
    clicked(): void {
      let test: TestObj = {
        name: "test",
        opened: false,
      };

      console.log(test.name);
    },
  },
};
</script>

<style scoped></style>
