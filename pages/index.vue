<template>
  <div>
    <!-- navbar -->
    <nav class="bg-gradient-to-r from-green-400 to-blue-500 p-4">
      <div class="container mx-auto">
        <nuxt-link
          to="/"
          class="text-gray-50 font-bold text-xl hover:text-white"
          >Cooking Tutorial</nuxt-link
        >
      </div>
      <Nuxtlayout>
        Some random text
      </Nuxtlayout>
    </nav>
    <!-- end of navbar -->
    <!-- content -->
    <div class="bg-gradient-to-r from-green-100 to-blue-200 px-8 lg:px-32">
      <main class="grid min-h-full py-8 lg:px-32">
        <div class="container bg-white rounded-md p-10">
          <div class="w-full text-center">
            <span class="page-title"
              >Resep Cheese Burger Ala IN-N-OUT California Amerika [Sausnya
              Special]</span
            >
          </div>
          <div class="flow-root lg:p-6">
            <div class="float-left lg:w-1/2 sm:w-full">
              <h3 class="pt-2 subtitle lg:px-6">Bahan Saus</h3>
              <ul class="list-disc">
                <li>8 sdm mayonaise</li>
                <li>3 sdm saus tomat</li>
                <li>1 sdm saus sambal</li>
                <li>1 sdm kecap inggris / worcestershire sauce</li>
                <li>1 sdt bubuk paprika</li>
                <li>1 sdt bubuk bawang putih</li>
                <li>2 sdm gula</li>
                <li>1 sdm cuka</li>
                <li>2 sdm daun bawang cincang</li>
                <li>2 sdm pickles gherkins cincang</li>
                <li>Garam</li>
              </ul>
              <h3 class="pt-2 subtitle lg:px-6">Caramelized onion</h3>
              <ul class="list-disc">
                <li>3 buah bawang bombai, iris</li>
                <li>3 sdm minyak</li>
                <li>1 sdm mentega</li>
                <li>1 siung bawang putih, iris (opsional)</li>
                <li>Sejumput daun thyme (opsional)</li>
                <li>⅓ sdt garam</li>
                <li>¼ sdt merica</li>
              </ul>
              <h3 class="pt-2 subtitle lg:px-6">Bahan Lainnya</h3>
              <ul class="list-disc">
                <li>4 buah roti burger</li>
                <li>400 gr daging giling dengan lemak</li>
                <li>1 sdm mentega</li>
                <li>Lada hitam</li>
                <li>Garam</li>
                <li>Keju slice red cheddar</li>
                <li>Iceberg lettuce</li>
                <li>1 buah tomat, iris</li>
              </ul>
            </div>
            <div class="float-right lg:w-1/2 sm:w-full">
              <h3 class="pt-2 subtitle lg:px-6">Langkah Pembuatan</h3>
              <ol class="list-decimal">
                <li>
                  Untuk membuat saus, campurkan pickled gherkins dan daun bawang
                  cincang di dalam mangkuk kemudian tambahkan kecap inggris,
                  bubuk paprika, bubuk bawang putih, gula, dan cuka lalu aduk
                  rata. Masukkan saus sambal, saus tomat, dan mayonaise lalu
                  aduk hingga tercampur, boleh juga ditambahkan sedikit garam
                  jika dirasa perlu
                </li>
                <li>
                  Untuk membuat caramelized onion, panaskan minyak kemudian
                  tumis bawang bombai iris dengan api besar hingga layu lalu
                  tambahkan bawang putih dan daun thyme kemudian bumbui dengan
                  garam dan merica
                </li>
                <li>
                  Kecilkan api, dan masak bawang hingga kecokelatan sambil
                  sesekali diaduk dan tambahkan mentega lalu matikan api
                </li>
                <li>
                  Untuk membuat patty, ambil daging giling (ukuran disesuaikan
                  dengan besar roti burger) lalu lempar-lemparkan dengan
                  menggunakan kedua tangan supaya menyatu kemudian grill lalu
                  pipihkan dengan spatula dan bumbui dengan garam dan lada hitam
                </li>
                <li>
                  Balikkan patty dan beri keju red cheddar diatasnya lalu masak
                  hingga matang dan keju meleleh. Patty bisa ditutup dengan pan
                  supaya keju cepat meleleh
                </li>
                <li>
                  Belah dua roti burger, kemudian panggang dengan sedikit
                  mentega hingga bagian dalamnya kecokelatan
                </li>
                <li>
                  Susun roti burger, olesi dengan saus kemudian tambahkan tomat,
                  iceberg lettuce, daging patty, caramelized onion, saus,
                  sedikit lada hitam, dan tutup dengan roti burger
                </li>
                <li>Cheese burger siap disajikan</li>
              </ol>
            </div>
          </div>
          <div class="container mt-8">
            <div class="grid place-items-center">
              <iframe
                class="w-full lg:w-3/6 aspect-video rounded"
                src="https://www.youtube.com/embed/KiHBmYx_G9k"
                title="YouTube video player"
                frameborder="0"
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
                allowfullscreen
              ></iframe>
            </div>
          </div>
        </div>
      </main>
    </div>
    <!-- end of content -->
    <!-- Footer -->
    <footer class="bg-gray-200 text-black py-4">
      <div class="container mx-auto text-center">
        <p>&copy; 2023 Cooking Tutorial. All rights reserved.</p>
      </div>
    </footer>
    <!-- end of footer -->
  </div>
</template>

<style lang="postcss" scoped>
.page-title {
  @apply font-bold text-lg;
}
.subtitle {
  @apply font-bold;
}
</style>
