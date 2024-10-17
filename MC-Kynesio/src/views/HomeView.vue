<script setup>
import WelcomeComponent from '@/components/WelcomeComponent.vue';
import SessionComponent from '@/components/SessionComponent.vue';
import PresentationComponent from '@/components/PresentationComponent.vue';
import OfficeComponent from '@/components/OfficeComponent.vue';
import PricesComponent from '@/components/PricesComponent.vue';
import KynesioComponent from '@/components/KynesioComponent.vue';

</script>

<template>
<div class="Main-container">
  
  <WelcomeComponent />
  <KynesioComponent />
  <SessionComponent />
  <PresentationComponent />
  <OfficeComponent />
  <PricesComponent />

</div>

</template>
<style scoped>
.main-container {
  display: flex;
  flex-direction: column;
}
</style>
