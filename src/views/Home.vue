<template>

    <main class="wrapper">

      <h1>Recommended</h1>

      <div class="recommended">

        <ProductCard
          v-for="(product, index) in inventory.slice(0, 3)"
          :key="product.id"
          class="card"
          :index="index"
          :product="product"
          :addToCart="addToCart"
        />

      </div>

    </main>

</template>

<script>

import ProductCard from '@/components/ProductCard.vue'

export default {
  props: ['inventory', 'addToCart'],
  components: {
    ProductCard
  }
}

</script>
