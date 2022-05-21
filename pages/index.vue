<template>
  <div class="app">
    <!-- Header -->
    <section>
      <div class="w-full h-7 bg-blue-axa"></div>
      <div>
        <div class="w-full bg-gray-axa py-4 flex justify-end">
          <button
            class="flex items-center justify-between bg-blue-axa text-white text-sm px-3 py-3 rounded-lg mx-5"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              class="h-5 w-5"
              fill="none"
              viewBox="0 0 24 24"
              stroke="currentColor"
              stroke-width="2"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M15 19l-7-7 7-7"
              />
            </svg>
            Kembali ke Pilihkartu
          </button>
        </div>
        <div class="flex items-end mx-auto px-10">
          <img src="~/assets/img/logo.png" alt="logo" class="-mt-12" />
          <div class="uppercase text-blue-axa ml-3">
            <h3 class="text-xl">
              Dapatkan Asuransi Gratis dari AXA Life indonesia
            </h3>
            <h2 class="text-3xl">untuk Pemegang Kartu Kredit</h2>
          </div>
        </div>
      </div>
    </section>
    <!-- Slider -->
    <div class="mt-10">
      <img src="~/assets/img/slides.png" alt="slides" width="100%" />
    </div>
    <!-- Benefits -->
    <div class="my-10 relative">
      <div class="container mx-auto">
        <h2 class="text-2xl font-bold text-center mb-10">
          Keuntungan mendaftar
          <span class="text-blue-axa">AXA Life indonesia</span> di Pilihkartu
        </h2>

        <!-- List -->
        <div class="grid grid-cols-2 gap-10">
          <div class="flex items-center justify-end">
            <p class="mr-5 text-right">
              Diberikan gratis secara cuma-cuma tanpa premi,
              <span class="font-bold">Premi : Rp. 0,-</span>
            </p>
            <img src="~/assets/img/icon_1.png" alt="icon-1" />
          </div>

          <div class="flex items-center">
            <img src="~/assets/img/icon_4.png" alt="icon-4" />
            <p class="ml-5">
              Pendaftar yang lolos verifikasi dari Tim AXA berhak mendapat
              perlindungan Asuransi kecelakaan diri
              <span class="font-bold">Selama 3 bulan.</span>
            </p>
          </div>

          <div class="flex items-center justify-end">
            <p class="mr-5 text-right">
              Santunan meninggal dunia akibat kecelakaan sebesar
              <span class="font-bold"> Rp 25.000.000,-</span> (dua puluh lima
              juta rupiah).
            </p>
            <img src="~/assets/img/icon_2.png" alt="icon-2" />
          </div>

          <div class="flex items-center">
            <img src="~/assets/img/icon_5.png" alt="icon-5" />
            <p class="ml-5">
              <span class="font-bold">Tanpa ada masa tunggu,</span> perlindungan
              yang didapatkan dimulai sejak polis aktif.
            </p>
          </div>

          <div class="flex items-center justify-end">
            <p class="mr-5 text-right">
              Perlindungan <span class="font-bold">Asuransi GRATIS</span> akan
              diberikan kepada pemegang kartu kredit yang mendaftar program AXA
              Care Protection melalui pilihkartu.com
            </p>
            <img src="~/assets/img/icon_3.png" alt="icon-3" />
          </div>

          <div class="flex items-center">
            <img src="~/assets/img/icon_6.png" alt="icon-6" />
            <p class="ml-5">
              <span class="font-bold">Bukan penawaran </span>melainkan pemberian
              secara cuma-cuma kepada nasabah ter-registrasi via Pilihkartu.com
              yang sudah memiliki kartu kredit.
            </p>
          </div>
        </div>
      </div>
      <img
        src="~/assets/img/benefit.png"
        alt="benefit"
        class="absolute top-0 right-2"
      />
    </div>
    <!-- About -->
    <div class="bg-about relative">
      <div class="container mx-auto">
        <h2 class="text-2xl font-bold text-center py-10">
          Tentang <span class="text-blue-axa">AXA Care Protection</span>
        </h2>
        <p class="text-center">
          Program asuransi gratis AXA Care Protection merupakan program
          perlindungan berupa asuransi kecelakaan dari asuransi AXA Life
          Indonesia. Peserta yang lolos verifikasi akan mendapatkan benefit
          berupa uang pertanggungan bila terjadi kecelakaan yang mengakibatkan
          meninggal dunia.
        </p>
        <div class="flex justify-center py-10">
          <button
            class="text-2xl bg-blue-axa text-white p-4 rounded-xl shadow-btn"
          >
            DAFTAR SEKARANG JUGA!
          </button>
        </div>
      </div>
      <img
        src="~/assets/img/about.png"
        alt="about"
        class="absolute left-4 top-6"
      />
    </div>
    <!-- Form -->
    <div class="container mx-auto mb-10">
      <h2 class="text-2xl font-bold text-center pt-10 pb-5">
        Dapatkan Perlindungan
        <span class="text-blue-axa">AXA Care Protection</span> Sekarang
      </h2>
      <p class="text-center">Cukup isi data diri Anda pada form dibawah ini</p>

      <!-- Form Section -->
      <div class="flex flex-col space-y-5 py-10">
        <div class="flex items-center justify-center">
          <div class="w-label">
            <label for="name"> Nama Lengkap </label>
          </div>
          <input
            type="text"
            class="border border-gray-axa px-3 h-10 ml-8 w-full"
          />
        </div>
        <div class="flex items-center justify-center">
          <div class="w-label">
            <label for="date"> Tanggal Lahir </label>
          </div>
          <input
            type="date"
            class="border border-gray-axa px-3 h-10 ml-8 w-full"
          />
        </div>
        <div class="flex items-center justify-center">
          <div class="w-label">
            <label for="email"> Email </label>
          </div>
          <input
            type="email"
            class="border border-gray-axa px-3 h-10 ml-8 w-full"
          />
        </div>
        <div class="flex items-center justify-center">
          <div class="w-label">
            <label for="phone"> Nomor Ponsel </label>
          </div>
          <input
            type="phone"
            class="border border-gray-axa px-3 h-10 ml-8 w-full"
          />
        </div>
        <div class="flex items-center justify-center">
          <div class="w-label">Memiliki Kartu Kredit</div>
          <div class="w-full flex items-center">
            <div
              v-for="item in options"
              :key="item.value"
              class="flex items-center"
            >
              <input type="checkbox" :value="item.value" class="h-10 ml-8" />
              <div class="flex ml-3">
                <span class="">{{ item.text }}</span>
              </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Syarat -->
      <div class="ml-72 space-y-3">
        <a href="#" class="text-blue-axa underline italic"
          >Syarat & Ketentuan Aplikasi</a
        >
        <div>
          <input type="checkbox" />
          <span class="text-sm">
            Saya mengetahui dan menyetujui syarat dan ketentuan diatas serta
            bersedia dihubungi oleh PT. AXA Life Indonesia untuk mendapatkan
            penjelasan tentang produk dan informasi lainnya
          </span>
        </div>
        <button class="bg-blue-axa text-white p-4 rounded-xl w-40">
          Kirim
        </button>
        <p class="text-sm text-gray-500">
          * Promo ini hanya berlaku bagi pemegang atau pemilik kartu kredit
          Syarat dan ketentuan lain diatur sebagaimana tertulis pada bagian
          syarat dan ketentuan. PT. AXA Life Indonesia terdaftar & diawasi oleh
          Otoritas Jasa keuangan (OJK)
        </p>
      </div>
    </div>
    <!-- Steps -->
    <div class="bg-gray-axa">
      <div class="container mx-auto pb-10">
        <h2 class="text-2xl font-bold text-center py-10">
          4 langkah mudah mendapatkan Asuransi
          <span class="text-blue-axa">AXA Life Indonesia</span> di Pilihkartu
        </h2>
        <div class="flex justify-center py-10">
          <img src="~/assets/img/langkah.png" alt="langkah" />
        </div>
      </div>
    </div>
    <!-- Footer -->
    <footer class="h-10 bg-blue-axa flex items-center">
      <div class="container mx-auto text-white">
        Copyright (c) 2017 Pilihkartucom and AXA All Rights Reserved
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      options: [
        { text: 'VISA', value: 'visa' },
        { text: 'MASTERCARD', value: 'mastercard' },
        { text: 'BCA CARD', value: 'bca' },
        { text: 'Lainnya', value: 'other' },
      ],
    }
  },
}
</script>

<style lang="scss" scoped>
.bg-about {
  background-color: #f4f7fd;
}
.shadow-btn {
  box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
  -webkit-box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
  -moz-box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
}
.w-label {
  width: 20%;
}
</style>
