<template>
  <div class="flex-col w-full h-full bg-gray-100 dark:bg-gray-900">
    <HeaderComponents />
    <div class="flex gap-[20px]">
      <Sidebar  />
      <Product  />
    </div>
  </div>
</template>
<script>
import HeaderComponents from '@/components/HeaderComponents.vue'
import Product from '@/components/Product.vue';
import Sidebar from '@/components/Sidebar.vue';
export default {
  name: 'HomeView',
  components: {
    // Heroicons
    HeaderComponents,
    Sidebar,
    Product,
  },
}
</script>
<style scoped></style>
