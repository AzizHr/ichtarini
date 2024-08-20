<script setup>
import Navbar from "./components/Navbar.vue";
import Filters from "./components/Filters.vue";
import Products from "./pages/Products.vue";
import Footer from "./components/Footer.vue";
import Pagination from "./components/Pagination.vue";
</script>

<template>
  <Navbar />

  <div class="here-image">
    <div dir="rtl" class="section">
      <h3 class="text-white fs-1">مرحبا بكم في موقعنا</h3>
      <p class="text-white fs-5 mt-3">
        اكتشف مجموعة واسعة من المنتجات المميزة التي تلبي جميع احتياجاتك. نحن هنا لنقدم لك
        تجربة تسوق فريدة ومريحة، تجمع بين الجودة والتنوع بأسعار تنافسية.
      </p>
      <button type="button" class="btn btn-success btn-lg mt-4">تصفح منتجاتنا</button>
    </div>
  </div>

  <Filters />

  <Products />

  <Pagination />

  <Footer />
</template>

<style scoped>
.here-image {
  width: 100%;
  height: 100vh;
  background-image: url("./assets/1297888.jpg");
  background-size: cover;
  background-position: center;
}

.section {
  padding-top: 10rem;
  padding-right: 4rem;
}
p {
  width: 35%;
}
</style>
