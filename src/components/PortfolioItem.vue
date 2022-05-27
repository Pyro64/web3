<template>
  <div class="portfolio">
    <div class="portfolio__block">
      <div class="portfolio__name">Portfolio</div>
      <div class="portfolio__item">
        <div class="portfolio__price">$ 10,249.94</div>
        <div class="down">2.49%</div>
      </div>
    </div>
    <div class="portfolio__icon">
      <img :src="bar" alt="bar" />
    </div>
  </div>
</template>

<script>
import bar from "../assets/icon/bar.svg";
export default {
  setup() {
    return {
      bar,
    };
  },
};
</script>

<style lang="scss" scoped></style>
