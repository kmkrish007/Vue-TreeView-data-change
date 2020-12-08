<template>
  <div id="app">
    <Treeview/>
  </div>
</template>

<script>
import Treeview from "./components/Treeview";

export default {
  name: "App",
  components: {
    Treeview
  }
};
</script>

<style>
#app {
  height: 100%;
}
</style>
