<template>
  <my-header />
  <div class="container">
    <description-item />
    <portfolio-item />
    <coin-list />
  </div>
</template>
<script>
import CoinList from "./components/CoinList.vue";
import MyHeader from "./components/MyHeader.vue";
import DescriptionItem from "./components/DescriptionItem.vue";
import PortfolioItem from "./components/PortfolioItem.vue";
export default {
  components: {
    MyHeader,
    CoinList,
    DescriptionItem,
    PortfolioItem,
  },
  setup() {},
};
</script>
<style src="./styles/style.scss"></style>
