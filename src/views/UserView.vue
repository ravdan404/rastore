<template>
  <HeaderComponents />
  <div class="User">
    <h1>User Page {{ userId }}</h1>
  </div>
</template>
<script>
import HeaderComponents from '@/components/HeaderComponents.vue'
export default {
  name: 'User',
  components: {
    HeaderComponents,
  },
  data() {
    return {
      userId: this.$route.params.id,
    }
  },
  watch: {
    '$route.params.id'(newId) {
      this.userId = newId
    },
  },
}
</script>
<style scoped></style>
