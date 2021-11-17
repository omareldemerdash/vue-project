<template>
  <section class="slider text-center position-relative text-uppercase">
    <b-container class="position-absolute top-50 start-50 translate-middle">
      <h3>design | development | photography</h3>
      <h1 class="mt-4 mb-4">creativity have a new level</h1>
      <a class="btn career">preview</a>
      <a class="btn career">get theme</a>
    </b-container>
  </section>
</template>
<script>
export default {
  name: "HomeComp",
};
</script>
<style scoped>
.slider {
  background-image: url("../assets/img/header.jpg");
  height: 90vh;
  background-color: var(--sec-color--);
  background-blend-mode: multiply;
  -webkit-background-blend-mode: multiply;
}
.slider h3{
color: var(--white--);
font-size:var(--default-font-size);
}
.slider h1{
  color: var(--white--);
  font-size: calc(var(--default-font-size) + 25px);
}
.slider .career{
  color: var(--white--);
  border: 1px solid var(--white--);
  margin:0 1%;
}
.slider .career:hover{
  background-color: var(--main-color--);
  transition: all .5s ease-in-out;
}
</style>
