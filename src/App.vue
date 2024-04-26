<script setup>
import TheNav from './components/TheNav.vue'
import TheHeader from './components/TheHeader.vue'
import TheForm from './components/TheForm.vue'
</script>
<template>
  <TheHeader />
  <section class="bg-blueGray-50 relative pt-12">
    <div class="flex flex-wrap items-center">
      <div class="ml-auto mr-auto w-full px-4 md:w-4/12">
        <img alt="..." class="max-w-full rounded-lg shadow-2xl shadow-black" src="./assets/about-img2.jpg" />
      </div>
      <div class="ml-auto mr-auto w-full px-4 md:w-5/12">
        <div class="md:pr-12">
          <!--<div
            class="mb-6 mt-8 inline-flex h-16 w-16 items-center justify-center rounded-full bg-pink-300 p-3 text-center text-pink-600 shadow-lg"
          >
            <i class="fas fa-rocket text-xl"></i>
          </div>-->
          <div class="pt-5 text-3xl font-semibold sm:text-xl md:text-2xl">
            Dzień dobry ❤ Nazywam się Margarita jestem kosmetologiem z wykształceniem medycznym.
            Specjalizuję się w depilacji laserowej - znam skuteczne metody pozbywania się
            owłosienia. Oferuję także różnorodne zabiegi kosmetologiczne: oczyszczanie, peelingi,
            zabiegi pielęgnacyjne , masaże oraz mezoterapię.
          </div>

          <ul class="mt-6 list-none">
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"><i
                      class="fas fa-fingerprint"></i></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">Kocmetoligia</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"><i
                      class="fab fa-html5"></i></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">Depilaciya</h4>
                </div>
              </div>
            </li>
            <li class="py-2">
              <div class="flex items-center">
                <div>
                  <span
                    class="mr-3 inline-block rounded-full bg-pink-200 px-2 py-1 text-xs font-semibold uppercase text-pink-600"><i
                      class="far fa-paper-plane"></i></span>
                </div>
                <div>
                  <h4 class="text-blueGray-500">Iglo ekaliwanie</h4>
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

  <section>
    <h3
      class="text-blueGray-500 mt-4 justify-center px-6 pt-5 text-center text-3xl font-semibold leading-relaxed sm:text-xl md:text-2xl">
      Zapraszam do skorzystania z profesjonalnych usług w moim gabinecie oraz do dobrania
      skutecznych produktów do pielęgnacji domowej, uwzględniając indywidualne
      potrzeby twojej skóry.
    </h3>
  </section>

  <section class="bg-blueGray-50 relative flex pt-12 max-w-screen-xl mx-auto ">
    <div class=" block  mb-10 items-center w-1/2">
      <div class="ml-auto mr-auto w-full px-4 md:">
        <div class="md:pl-1">
          <!--Start Table-->
          <h3 class="text-3xl font-semibold justify-between  ">Cennik Depilacja
          </h3>
          <p class="text-blueGray-500 mt-4 text-lg leading-relaxed">
          <div class="overflow-x-auto flex">
            <table class="border-collapse border rounded-lg ">
              <thead>
                <tr class="bg-gray-200">
                  <th class="border p-3">#</th>
                  <th class="border p-3">Poslygy</th>
                  <th class="border p-3">Cena (zł)</th>
                </tr>
              </thead>
              <tbody>
                <tr>
                  <td class="border p-3">1</td>
                  <td class="border p-3">Depilacja Wasik</td>
                  <td class="border p-3">70</td>
                </tr>
                <tr>
                  <td class="border p-3">2</td>
                  <td class="border p-3">Broda</td>
                  <td class="border p-3">70</td>
                </tr>
                <tr>
                  <td class="border p-3">3</td>
                  <td class="border p-3">Policzki</td>
                  <td class="border p-3">70</td>
                </tr>
                <tr>
                  <td class="border p-3">4</td>
                  <td class="border p-3">Twarz cała</td>
                  <td class="border p-3">180</td>
                </tr>
                <tr>
                  <td class="border p-3">5</td>
                  <td class="border p-3">Szyja (obszar z tylu lub z przodu)</td>
                  <td class="border p-3">100</td>
                </tr>
                <tr>
                  <td class="border p-3">6</td>
                  <td class="border p-3">Szyja cała</td>
                  <td class="border p-3">180</td>
                </tr>
                <tr>
                  <td class="border p-3">7</td>
                  <td class="border p-3">Pachy</td>
                  <td class="border p-3">100</td>
                </tr>
                <tr>
                  <td class="border p-3">8</td>
                  <td class="border p-3">Ręce cale</td>
                  <td class="border p-3">180</td>
                </tr>
                <tr>
                  <td class="border p-3">9</td>
                  <td class="border p-3">Ręce do łokcia</td>
                  <td class="border p-3">150</td>
                </tr>
                <tr>
                  <td class="border p-3">10</td>
                  <td class="border p-3">Dekolt</td>
                  <td class="border p-3">150</td>
                </tr>
                <tr>
                  <td class="border p-3">11</td>
                  <td class="border p-3">Otoczki brodawek sutkowych</td>
                  <td class="border p-3">70</td>
                </tr>

                <tr>
                  <td class="border p-3">12</td>
                  <td class="border p-3">Brzuch</td>
                  <td class="border p-3">150</td>
                </tr>


              </tbody>
            </table>
          </div>
          <!--End Table-->
          </p>
        </div>
      </div>
    </div>

    <div class="block mb-10 items-center w-1/2">
      <div class="ml-auto mr-auto w-full px-4 md:">
        <div class="md:pl-1">
          <!--Start Table-->
          <h3 class="text-3xl font-semibold justify-between  ">Cennik Depilacja
          </h3>
          <p class="text-blueGray-500 mt-4 text-lg leading-relaxed">
          <div class="overflow-x-auto flex">
            <table class="border-collapse border rounded-lg ">
              <thead>
                <tr class="bg-gray-200">
                  <th class="border p-3">#</th>
                  <th class="border p-3">Poslygy</th>
                  <th class="border p-3">Cena (zł)</th>
                </tr>
              </thead>
              <tbody>

              </tbody>
            </table>
            <ul class="list-disc list-inside">
              <li class="border p-3">17 Bikini całkowite 190</li>
              <li class="border p-3">18 Bikini nie całkowite 160</li>
              <li class="border p-3">19 Obszar tonowy 100</li>
              <li class="border p-3">20 Wargi sromowe 90</li>
              <li class="border p-3">21 Szpara międzypośladkowa 90</li>
              <li class="border p-3">22 Pośladki 150</li>
              <li class="border p-3">23 Cate nog 290</li>
              <li class="border p-3">24 Łydki/Uda 160</li>
            </ul>
          </div>
          <!--End Table-->
          </p>
        </div>
      </div>
      <ul class="list-disc list-inside">
        <li class="border p-3">17 Bikini całkowite 190</li>
        <li class="border p-3">18 Bikini nie całkowite 160</li>a
        <li class="border p-3">19 Obszar tonowy 100</li>
        <li class="border p-3">20 Wargi sromowe 90</li>
        <li class="border p-3">21 Szpara międzypośladkowa 90</li>
        <li class="border p-3">22 Pośladki 150</li>
        <li class="border p-3">23 Cate nog 290</li>
        <li class="border p-3">24 Łydki/Uda 160</li>
      </ul>
    </div>
    <footer class="relative mt-8 pb-6 pt-8">
      <!-- Your footer remains unchanged -->
    </footer>
  </section>

  <section class="bg-blueGray-50 relative pt-12 ">


    <footer class="relative mt-8 pb-6 pt-8">
      <!-- Your footer remains unchanged -->
    </footer>
  </section>

  <TheForm />

  <TheNav />
</template>
