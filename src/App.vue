<script>
import NavigationBar from "./components/NavigationBar.vue"
export default {
  components: { NavigationBar }
}
</script>

<template>
  <div>
    <NavigationBar />
    <RouterView></RouterView>
  
  </div>
</template>
