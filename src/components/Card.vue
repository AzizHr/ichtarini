<script setup></script>

<template>
  <div class="col-lg-3 col-md-4 col-sm-12 mb-4">
    <div class="card pb-2">
      <img src="../assets/1297888.jpg" alt="التفاح" class="card-img" />
      <div class="px-2">
        <h4 class="py-2">التفاح</h4>
        <p>8,50 درهم</p>
        <div class="d-flex justify-content-between">
            <button type="button" class="btn btn-info">إضافة للسلة</button>
            <span class="text-secondary fs-6">توصيل مجاني</span>
        </div>
        
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  border-radius: 4px;
  border: none;
  box-shadow: 0px 0px 1px 0px black;
}
.card-img {
  width: 100%;
  height: 44%;
  object-fit: cover;
}
</style>
