<template>
  <b-container class="bv-example-row text-center">
    <b-row class="boxes pt-5 pb-5">
      <b-col lg="4" md="6" sm="12">
        <div class="box">
          <img class="p-4" src="../../assets/img/idea.svg" alt="idea" />
          <h4 class="p-2">IDEA</h4>
          <p class="p-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Totam
            velit ea rem consequuntur dignissimos praesentium, quas, explicabo
            unde perspiciatis laudantium doloremque? Sapiente repudiandae, saepe
            architecto necessitatibus tempore nemo nulla exercitationem.
          </p>
        </div>
      </b-col>
      <b-col lg="4" md="6" sm="12">
        <div class="box">
          <img class="p-4" src="../../assets/img/work.svg" alt="work" />
          <h4 class="p-2">WORK</h4>
          <p class="p-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Totam
            velit ea rem consequuntur dignissimos praesentium, quas, explicabo
            unde perspiciatis laudantium doloremque? Sapiente repudiandae, saepe
            architecto necessitatibus tempore nemo nulla exercitationem.
          </p>
        </div>
      </b-col>
      <b-col lg="4" md="6" sm="12">
        <div class="box">
          <img class="p-4" src="../../assets/img/deliver.svg" alt="deliver" />
          <h4 class="p-2">DELIVER</h4>
          <p class="p-3">
            Lorem ipsum dolor sit, amet consectetur adipisicing elit. Totam
            velit ea rem consequuntur dignissimos praesentium, quas, explicabo
            unde perspiciatis laudantium doloremque? Sapiente repudiandae, saepe
            architecto necessitatibus tempore nemo nulla exercitationem.
          </p>
        </div>
      </b-col>
    </b-row>
  </b-container>
</template>
<script>
export default {
  name: "Card",
};
</script>
<style scoped>
.boxes .box {
  background-color: var(--white--);
}
.boxes .box img{
  border-bottom: 2px solid var(--main-color--);

}

</style>
