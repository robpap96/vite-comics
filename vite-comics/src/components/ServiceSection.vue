<script>
export default {
  name: "ServiceSection",
  components: {
    //AppName
  },
  data() {
    return {
      items: [
        {
          serviceIcon: "src/assets/buy-comics-digital-comics.png",
          serviceName: "Digital Comics",
        },
        {
          serviceIcon: "src/assets/buy-comics-merchandise.png",
          serviceName: "DC Merchandise",
        },
        {
          serviceIcon: "src/assets/buy-comics-shop-locator.png",
          serviceName: "Subscription",
        },
        {
          serviceIcon: "src/assets/buy-comics-subscriptions.png",
          serviceName: "Comic Shop Locator",
        },
        {
          serviceIcon: "src/assets/buy-dc-power-visa.svg",
          serviceName: "DC Power Visa",
        },
      ],
    };
  },
};
</script>

<template>
  <section>
    <div class="container">
      <ul>
        <li v-for="(item, index) in items">
          <div>
            <img :src="item.serviceIcon" alt="" />
          </div>
          <div>
            {{ item.serviceName }}
          </div>
        </li>
      </ul>
    </div>
  </section>
</template>

<style lang="scss" scoped>
section {
  color: white;
  background-color: #0282f9;
  padding: 50px 100px;
}
ul {
  display: flex;
  align-items: center;
  justify-content: center;
}
li {
    width: calc(100% / 5 - 50px);
    display: flex;
    justify-content: center;
    align-items: center;
}
img {
  width: 70px;
  margin-right: 10px;
}
img:last-of-type {
    width: 40%;
}
</style>
