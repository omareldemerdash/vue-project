<template>
  <section>
    <Caption />
    <Card />
  </section>
</template>
<script>
import Caption from "@/components/ServiceComp/CaptionComp.vue";
import Card from "@/components/ServiceComp/CardComp.vue";

export default {
  name: "Service",
  components: {
    Caption,
    Card,
  },
};
</script>
<style scoped>
section{
  background-color: var(--light-gray--);
  
}
</style>
