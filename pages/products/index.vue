<template>
  <div>
    <div class="container mt-5 pt-5">
      <LargeCardDisplay
        v-for="cardInfo in largeCardInfo.slice(0, 1)"
        :key="cardInfo.id"
        :cardsSection="cardInfo"
      />

      <SmallCardDisplay
        v-for="cardInfo in smallCardInfo"
        :key="cardInfo.id"
        :cardsSection="cardInfo"
      />
    </div>
  </div>
</template>
<script>
import { largeCardSections, smallCardSections } from "~/assets/data";
export default {
  data() {
    return {
      largeCardInfo: largeCardSections,
      smallCardInfo: smallCardSections,
    };
  },
};
</script>
<style lang="">
</style>