<script setup lang="ts"></script>

<template>
  <header>
    <ul class="list">
      <li>
        <NuxtLink to="/">前台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/about">前台 About</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin">後台首頁</NuxtLink>
      </li>
      <li>
        <NuxtLink to="/admin/order">後台order</NuxtLink>
      </li>
    </ul>
  </header>
  <slot />
  <footer>
    admin footer
  </footer>
</template>

<style scoped></style>
