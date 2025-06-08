<template>
  <div class="flex-col w-full px-10 py-8 space-y-8 dark:text-white text-gray-900">
    <div class="md:flex hidden justify-between">
      <div class="flex items-center gap-1 text-gray-500 text-md">
        <a href="/">Main</a><span>-</span><a href="#">Catalog</a>
      </div>
      <div class="flex items-center gap-5">
        <div class="flex items-center gap-2">
          <button class="text-blue-500">
            <QueueListIcon class="size-5.5" />
          </button>
          <button class="text-blue-500">
            <Squares2X2Icon class="size-5.5" />
          </button>
        </div>
        <button class="flex items-center gap-1 font-medium">
          Popular First <ChevronDownIcon class="size-4" />
        </button>
      </div>
    </div>
    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 xl:grid-cols-4 gap-6">
      <ProductItems />
      <ProductItems />
      <ProductItems />
      <ProductItems />
      <ProductItems />
      <ProductItems />
      <ProductItems />
      <ProductItems />
    </div>
  </div>
</template>

<script>
import ProductItems from './ProductItems.vue'
import { ChevronDownIcon, QueueListIcon, Squares2X2Icon, } from '@heroicons/vue/24/outline'

export default {
  name: 'Product',
  components: {
    ProductItems,
    // Heroicons
    QueueListIcon,
    Squares2X2Icon,
    ChevronDownIcon
  },
}
</script>

<style></style>
