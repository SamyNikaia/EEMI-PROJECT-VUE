<script setup>
import ProductCard from '@/components/Home/ProductCard.vue'
</script>

<template>
  <section class="py-12">
    <div class="max-w-7xl mx-auto px-4">
      <h3 class="text-2xl font-semibold mb-8 text-center">Produits en vedette</h3>
      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
        <!-- Produit -->
        <ProductCard />
        <ProductCard />
      </div>
    </div>
  </section>
</template>
