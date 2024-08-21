<script setup>
import { ref } from "vue";

const isOpen = ref(false);
</script>

<template>
  <nav class="bg-gray-100" dir="rtl">
    <div class="container mx-auto flex items-center justify-between p-4">
      <a class="flex items-center text-xl font-bold" href="#">
        <img src="../assets/logo.png" alt="logo" class="w-10 h-10 mr-2" />
        إشتريني
      </a>
      <button
        class="text-gray-700 focus:outline-none lg:hidden"
        @click="isOpen = !isOpen"
      >
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-6 w-6"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16"
          />
        </svg>
      </button>
      <div
        :class="{ block: isOpen, hidden: !isOpen }"
        class="w-full lg:flex lg:items-center lg:w-auto lg:block lg:static"
      >
        <ul class="lg:flex lg:space-x-4 lg:space-x-reverse lg:ml-auto lg:mr-0">
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              >الصفحة الرئيسية</a
            >
          </li>
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              >الخضروات</a
            >
          </li>
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              >الفواكه</a
            >
          </li>
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              >حول</a
            >
          </li>
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              >تواصل معنا</a
            >
          </li>
          <li class="nav-item">
            <a
              class="block py-2 px-4 text-gray-700 hover:bg-gray-200 lg:inline lg:p-2"
              href="#"
              ><i class="fa-solid fa-cart-shopping"></i
            ></a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<style></style>
