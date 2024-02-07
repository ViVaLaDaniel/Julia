<script setup>
import TheNav from './components/TheNav.vue'
import TheHeader from './components/TheHeader.vue';
import TheForm from './components/TheForm.vue';

</script>
<template>
<TheHeader/>
  <section class="bg-blueGray-50 relative pt-12">
    <div class="flex flex-wrap items-center">
      <div class="ml-auto mr-auto w-full px-4 md:w-4/12">
        <img alt="..." class="max-w-full rounded-lg  shadow-2xl shadow-black " src="./assets/Pict/Photo2.png" />
      </div>
      <div class="ml-auto mr-auto w-full px-4 md:w-5/12">
        <div class="md:pr-12">
          <div
            class="mb-6 mt-8 inline-flex h-16 w-16 items-center justify-center rounded-full bg-pink-300 p-3 text-center text-pink-600 shadow-lg"
          >
            <i class="fas fa-rocket text-xl"></i>
          </div>
          <h3 class="text-3xl font-semibold">Лучшая компания на свете</h3>
          <p class="text-blueGray-500 mt-4 text-lg leading-relaxed">
            Мы делаем лучшие игрушки в мире.Тепло добро и уют для вас и вашешо сердца
          </p>
          <ul class="mt-6 list-none">
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"
                    ><i class="fas fa-fingerprint"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">С любовью</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"
                    ><i class="fab fa-html5"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">С заботой</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"
                    ><i class="far fa-paper-plane"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">От сердца</h4>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <footer class="relative mt-8 pb-6 pt-8">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap items-center justify-center md:justify-between">
          <div class="mx-auto w-full px-4 text-center md:w-6/12"></div>
        </div>
      </div>
    </footer>
  </section>

  <section class="bg-blueGray-50 relative pt-12">
    <div class="flex flex-wrap items-center">
      <div class="ml-auto mr-auto w-full px-4 md:w-5/12">
        <div class="md:pl-12">
          <!-- Updated to md:pl-12 to give padding to the left -->
          <div
            class="mb-6 mt-8 inline-flex h-16 w-16 items-center justify-center rounded-full bg-pink-300 p-3 text-center text-pink-600 shadow-lg"
          >
            <i class="fas fa-rocket text-xl"></i>
          </div>
          <h3 class="text-3xl font-semibold">A growing company</h3>
          <p class="text-blueGray-500 mt-4 text-lg leading-relaxed">
            The extension comes with three pre-built pages to help you get started faster. You can
            change the text and images and you're good to go.
          </p>
          <ul class="mt-6 list-none">
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"
                    ><i class="fas fa-fingerprint"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">С любовью</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"
                    ><i class="fab fa-html5"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">С заботой</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600 "
                    ><i class="far fa-paper-plane"></i
                  ></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">От сердца</h4>
                </div>
              </div>
            </li>
          </ul>
        </div>
      </div>
      <div class="ml-auto mr-auto w-full px-4 md:w-4/12">
        <!-- Moved this div to the right side -->
        <img alt="..." class="max-w-full rounded-lg shadow-2xl shadow-black " src="./assets/Pict/Pict2.png" />
      </div>
    </div>
    <footer class="relative mt-8 pb-6 pt-8">
      <!-- Your footer remains unchanged -->
    </footer>
  </section>
  
  <TheForm/>
  
  <TheNav />
  
</template>
