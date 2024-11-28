<script>

import LoginComponent from "@/components/LoginComponent.vue";

export default {
  components: { LoginComponent},
  data() {
    return {
      "LoginComponent": LoginComponent,
    };
  }
};


</script>

<template>
  <LoginComponent/>
</template>

