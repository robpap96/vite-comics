<script>
import HeroJumbotron from "./HeroJumbotron.vue";
import AppCard from "./AppCard.vue";
export default {
  name: "ContentSection",
  components: {
    HeroJumbotron,
    AppCard,
  },
  data() {
    return {};
  },
};
</script>

<template>
  <HeroJumbotron />
  <section>
    <div class="container">
      <AppCard />
    </div>
    <div >
      <button class="load-more-btn">LOAD MORE</button>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  color: white;
  padding: 50px 20px;
  background-color: #1c1c1c;
  text-align: center;
    .load-more-btn{
        color: white;
        font-size: 17px;
        font-weight: bold;
        background-color: #0282f9;
        padding: 10px 20px;
    }
}
.container {
  display: flex;
  flex-wrap: wrap;
  padding: 20px 0;
}

</style>
