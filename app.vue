<template>
  <div>
    <!-- <NuxtRouteAnnouncer /> -->
    <NuxtLink to="/">首頁</NuxtLink> |
    <NuxtLink to="/about">關於</NuxtLink> |
    <NuxtLink to="/person">Person</NuxtLink>
    <NuxtPage></NuxtPage>
  </div>
</template>

<script setup>
import '~/assets/all.scss';
</script>