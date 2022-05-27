<template>
  <div class="coin" v-for="coin in coins" :key="coin.id">
    <coin-item :coin="coin" />
  </div>
</template>

<script>
import CoinItem from "./CoinItem.vue";
import btc from "../assets/icon/eth.svg";
export default {
  components: {
    CoinItem,
  },
  setup() {
    const coins = [
      {
        id: 1,
        img: btc,
        name: "Bitcoin",
        price: "$ 2,638.02",
        value: "0.001942",
        reduction: "btc",
        percent: "0.02%",
        isRise: true,
      },
      {
        id: 1,
        img: btc,
        name: "Bitcoin",
        price: "$ 2,638.02",
        value: "0.001942",
        reduction: "btc",
        percent: "0.02%",
        isRise: true,
      },
      {
        id: 1,
        img: btc,
        name: "Bitcoin",
        price: "$ 2,638.02",
        value: "0.001942",
        reduction: "btc",
        percent: "0.02%",
        isRise: true,
      },
      {
        id: 1,
        img: btc,
        name: "Bitcoin",
        price: "$ 2,638.02",
        value: "0.001942",
        reduction: "btc",
        percent: "0.02%",
        isRise: true,
      },
      {
        id: 1,
        img: btc,
        name: "Bitcoin",
        price: "$ 2,638.02",
        value: "0.001942",
        reduction: "btc",
        percent: "0.02%",
        isRise: false,
      },
    ];
    return {
      coins,
    };
  },
};
</script>

<style lang="scss" scoped></style>
