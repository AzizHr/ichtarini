<script setup>
import Navbar from "./components/Navbar.vue";
import Filters from "./components/Filters.vue";
import Products from "./pages/Products.vue";
import Footer from "./components/Footer.vue";
import Pagination from "./components/Pagination.vue";
</script>

<template>
  <Navbar />

  <div class="here-image flex items-center justify-center text-right">
    <div class="section text-white">
      <h3 class="text-4xl">مرحبا بكم في موقعنا</h3>
      <p class="mt-3 hidden sm:block text-lg max-w-xs">
        اكتشف مجموعة واسعة من المنتجات المميزة التي تلبي جميع احتياجاتك. نحن هنا لنقدم لك
        تجربة تسوق فريدة ومريحة، تجمع بين الجودة والتنوع بأسعار تنافسية.
      </p>
      <button type="button" class="mt-4 btn btn-success sm:btn-lg">تصفح منتجاتنا</button>
    </div>
  </div>

  <Filters />

  <Products />

  <Pagination />

  <Footer />
</template>

<style scoped>
.here-image {
  @apply w-full h-screen bg-cover bg-center;
  background-image: url("./assets/1297888.jpg");
}
.section {
  @apply pt-40 pr-16 sm:pt-72 sm:pr-4;
}
</style>
