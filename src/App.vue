<template>
  <section>
    <NavBar></NavBar>
    <div>
      <router-view />
    </div>
  </section>
</template>

<script>
import NavBar from "@/components/Nav";
export default {
  components: { NavBar },
};
</script>

<style></style>
