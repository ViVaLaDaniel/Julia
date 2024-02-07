<script setup>
import { BxFacebookCircle, ReWhatsappFill, BxInstagramAlt, BsYoutube, BxTiktok, CoBrandPinterest } from '@kalimahapps/vue-icons';

const navItems = {
  facebook: BxFacebookCircle,
  whatsapp: ReWhatsappFill,
  instagram: BxInstagramAlt,
  youtube: BsYoutube,
  pinterest: CoBrandPinterest,
  tiktok: BxTiktok, 
};

const socialLinks = {
  facebook: 'https://www.facebook.com/profile.php?id=100092010186728',
  whatsapp: 'https://api.whatsapp.com/send?phone=48537617365',
  instagram: 'https://www.instagram.com/keit.handmade.gya?igsh=MTF4YnZxZm83YWwxOA==',
  youtube: 'https://www.youtube.com/@KeitHandMade',
  pinterest: 'https://pin.it/MxcHC35we',
  tiktok: 'https://www.tiktok.com/@keit.handmade_?_t=8jgR4IBsr8S&_r=1',
};
</script>

<template>
<nav class="sticky bottom-0 z-10 bg-white bg-opacity-80 text-3xl backdrop-blur-sm ">
  <ul class="flex items-center justify-around border-t">
    <li v-for="(icon, page) in navItems" :key="page" class="flex-1">
      <a :href="socialLinks[page]" target="_blank" class="flex flex-col items-center p-2 text-xs capitalize  ">
        <component :is="icon" class="h-6 w-6" /> {{ page }}
      </a>
    </li>
  </ul>
</nav>
</template>
