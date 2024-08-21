<script setup></script>

<template>
  <div dir="rtl" class="sm:px-5 px-3 py-4">
    <h4 class="text-lg font-semibold">منتجاتنا</h4>
    <div>
      <hr class="border-gray-300" />
    </div>

    <div dir="rtl" class="flex py-1 gap-3">
      <div class="w-1/4">
        <label for="categorySelect" class="form-label mt-4 text-right">الفئة</label>
        <select class="form-select block w-full mt-1 border-gray-300 rounded-md shadow-sm focus:border-blue-300 focus:ring focus:ring-blue-200">
          <option>فواكه</option>
          <option>خضراوات</option>
        </select>
      </div>

      <div class="w-1/4">
        <label for="priceSelect" class="form-label mt-4 text-right">السعر</label>
        <select class="form-select block w-full mt-1 border-gray-300 rounded-md shadow-sm focus:border-blue-300 focus:ring focus:ring-blue-200">
          <option>الأرخص</option>
          <option>الأغلى</option>
        </select>
      </div>

      <div class="w-1/4">
        <label for="deliverySelect" class="form-label mt-4 text-right">التوصيل</label>
        <select class="form-select block w-full mt-1 border-gray-300 rounded-md shadow-sm focus:border-blue-300 focus:ring focus:ring-blue-200">
          <option>مجاني</option>
          <option>مدفوع</option>
        </select>
      </div>
    </div>
  </div>
</template>

<style></style>
