<template>
  <img :src="coin.img" alt="reduction" />
  <div class="coin__block">
    <div class="coin__name">{{ coin.name }}</div>
    <div class="coin__price">{{ coin.price }}</div>
    <div class="coin__item">{{ coin.value }} {{ coin.reduction }}</div>
  </div>
  <div
    :class="{
      down: coin.isRise == false,
    }"
    class="up"
  >
    {{ coin.percent }}
  </div>
</template>

<script>
export default {
  props: {
    coin: {
      type: Object,
      required: true,
    },
  },
  setup() {
    return {};
  },
};
</script>

<style lang="scss" scoped></style>
