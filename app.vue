<template>
  <div>
    <!-- <ProductList /> -->
    <nav>
    <router-link to="/BlogPostsUi" class="nav-link">
      <button class="btn-nav">BlogPostsUi</button>
    </router-link>
  </nav>
    <NuxtPage />
  </div>
</template>

<script setup lang="ts">

import BlogPostsUi from "~/pages/BlogPostsUi.vue";
import BlogPosts from "~/pages/BlogPosts.vue";
import ProductList from "~/pages/ProductList.vue";
</script>

<style scoped>
.btn-nav {
  display: inline-block;
  width: 100%;
  padding: 8px 16px; 
  font-size: 14px; 
  font-weight: bold;
  color: #edecf0; 
  background-color: #4b4d4b; 
  border: 1px solid #5a5858; 
  border-radius: 5px; 
  cursor: pointer;
  text-decoration: none;
  transition: background-color 0.3s ease; 
}

.btn-nav:hover {
  background-color: #4a4a4a; 
}
</style>