<script>
import AppTitle from "./components/AppTitle.vue";
export default {
  components: {
    AppTitle
  },
  data(){
    return{
      title: "La mia prima app con Vite!"
    }
  }
}
</script>

<template>
<h1>{{ title }}</h1>
</template>

<style scoped>

</style>
