<template>
  <div class="packages">
    <NavbarComponent />
    <HeaderComponent />
    <OurPackages />
    <Footercomponent />
  </div>
</template>

<script>
import HeaderComponent from "@/components/HeaderComponent.vue";
import Footercomponent from "@/components/FooterComponent.vue";
import NavbarComponent from "@/components/NavbarComponent.vue";

import OurPackages from "@/components/packages/OurPackages.vue";
export default {
  components: {
    HeaderComponent,
    Footercomponent,
    NavbarComponent,
    OurPackages,
  },
};
</script>

<style></style>
