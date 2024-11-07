<script setup lang="ts"></script>

<template>
  <header>
    <ul class="list">
      <li>
        <NuxtLink to="/">前台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">前台About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin">後台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin/order">後台訂單</NuxtLink>
      </li>
    </ul>
  </header>
  <slot />
  <footer>
    前台footer
  </footer>
</template>

<style scoped></style>
