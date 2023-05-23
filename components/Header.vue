<template>
    <header class="bg-gray-200">
      <div class="container mx-auto">
        <nav class="flex justify-between h-[70px] items-center">
          <img src="../images/logo.png" alt="" class="font-bold w-[214px] h-[46px]">
          <ul class="flex gap-8 font-bold">
            <li><NuxtLink to="/course">Kurslar</NuxtLink></li>
            <li><NuxtLink to="/blog">Blog</NuxtLink></li>
            <li><NuxtLink to="/">Kirish</NuxtLink></li>
            <li class="mt-[-10px] flex justify-center items-center"><img src="../images/Dark_mode.svg" alt=""></li>
          </ul>
        </nav>
      </div>
    </header>
  </template>
  
  <script setup></script>
  
  <style lang="scss" scoped>
  .router-link-exact-active {
      font-weight: 800;
      background-color: white;
      padding: 10px;
      border-radius: 15px;
    }
    
    .logo {
      text-decoration: none !important;
    }
  
  </style>
  