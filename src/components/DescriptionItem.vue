<template>
  <div class="description">
    <div class="description__block">
      <div class="description__item">
        <div class="description__price">$ 4,249.94</div>
        <div class="percent">1.3%</div>
      </div>
      <div class="description__item">
        <div class="description__name">4.41942 BNB</div>
        <div class="description__name">0.0441942 ETH</div>
      </div>
    </div>
    <div class="description__icons">
      <div class="description__icon">
        <img :src="up" alt="up" />
      </div>
      <div class="description__icon">
        <img :src="down" alt="down" />
      </div>
    </div>
  </div>
</template>

<script>
import up from "../assets/icon/up.svg";
import down from "../assets/icon/down.svg";
export default {
  setup() {
    return {
      up,
      down,
    };
  },
};
</script>
