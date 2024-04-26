<!--<template>
    <header    class="sticky top-0 z-20 flex items-center justify-between border-b bg-white bg-opacity-80 p-3 backdrop-blur-sm">
    <a href="#">
      <img src="../assets/KaitHendMade.svg" alt="Logo" class="h-9" />
    </a>
    <a href="tel:=48537617365" class="text-lg">
      <div class="flex justify-center">+48537617365</div>
    </a>
  </header>
</template>-->
<script setup>
import { BsTelephoneInboundFill } from '@kalimahapps/vue-icons'
</script>

<template>
  <header
    class="sticky top-0 z-20 flex items-center justify-between border-b bg-white bg-opacity-80 p-3 backdrop-blur-sm"
  >
    <a href="#">
      <img src="../assets/logo4.png" alt="Logo" class="h-25" />
    </a>
    <!-- Для мобильных устройств -->
    <div class="flex-2-w-64 hidden items-center md:flex">
      <a href="tel:=48537617365" class="flex justify-center text-lg px-2   ">+48537617365</a>
    </div>
    <!-- Для мобильных устройств dd-->
    <div class="flex items-center md:hidden">
      <a href="tel:=48537617365">
        <BsTelephoneInboundFill class="h-5 w-5 fill-pink-400" />
      </a>
    </div>
  </header>
</template>
