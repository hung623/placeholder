<template>
  <div id="app">
      <div>
        <mainHeader/>
        <mainFooter/>
      </div>
    <router-view/>
  </div>
  
</template>
<style>
#app {
  display: flex;
  flex-direction: column;
  height: 100%;
}
</style>


<script>
import mainFooter from "@/components/footer.vue";
import mainHeader from "@/components/header.vue";

export default {
  name: "home",
  components: {
    mainFooter,
    mainHeader,
  }
};
</script>