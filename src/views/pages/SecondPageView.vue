<script>
import Se from "@/components/pages/FirstPageComponent.vue";
import SecondPageComponent from "@/components/pages/SecondPageComponent.vue";

export default {
  components: { SecondPageComponent},
  data() {
    return {
      "SecondPageComponent": SecondPageComponent,
    };
  }
};
</script>

<template>
    <SecondPageComponent/>
</template>

<style>
</style>

