<script setup>
import { BsTelephoneInboundFill } from '@kalimahapps/vue-icons'
</script>

<template>
  <header
    class="sticky top-0 z-20 flex items-center justify-between border-b bg-purple-400 bg-opacity-80 p-3 backdrop-blur-sm"
  >
    <a href="#">
      <img src="../assets/Keit_Hend_Made.svg" alt="Logo" class="h-9" />
    </a>
    <!-- Для мобильных устройств -->
    <div class="hidden items-center md:flex">
      <a href="tel:=48537617365" class="flex justify-center text-lg">+48537617365</a>
    </div>
    <!-- Для мобильных устройств -->
    <div class="flex items-center md:hidden">
      <a href="tel:=48537617365">
        <BsTelephoneInboundFill class="h-5 w-5 fill-pink-400" />
      </a>
    </div>
  </header>
</template>
