<script setup>
import { BsTelephoneInboundFill } from '@kalimahapps/vue-icons'
</script>

<template>
  <header class="sticky top-0 z-20 flex items-center justify-between border-b bg-white bg-opacity-80 p-3 backdrop-blur-sm">
    <a href="#">
      <img src="../assets/KaitHendMade.svg" alt="Logo" class="h-9" />
    </a>
    <!-- Для мобильных устройств -->
    <div class="hidden md:flex items-center">
      <a href="tel:=48537617365" class="text-lg flex justify-center">+48537617365</a>
    </div>
    <!-- Для мобильных устройств -->
    <div class="md:hidden flex items-center">
      <a href="tel:=48537617365">
        <BsTelephoneInboundFill class="h-5 w-5 fill-pink-400" />
      </a>
    </div>
  </header>
</template>
