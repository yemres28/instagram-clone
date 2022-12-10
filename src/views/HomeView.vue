<template>
  <div class="home">
    <br />
    <CustomText class="a1" tag="p">Deneme</CustomText>
    <CustomText tag="p" size="small">Deneme</CustomText>
    <CustomText tag="p" size="xsmall">Deneme</CustomText>
    <CustomText tag="p" size="xxsmall">Deneme</CustomText>
  </div>
</template>

<script>
import CustomText from "@/components/CustomText.vue";
export default {
  name: "HomeView",
  components: {
    CustomText,
  },
};
</script>
<style scoped>
.a1 {
  color: rgb(var(--jbb));
}
</style>
