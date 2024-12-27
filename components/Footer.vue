<template>
  <div>
  <!-- Footer pertama di luar carousel -->
 <footer class="bg-green-600 text-white py-10 mt-10">
      <div class="container mx-auto px-4">
        <div class="flex flex-wrap justify-between">
          <!-- Alamat Section -->
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h2 class="font-bold mb-2">Alamat</h2>
            <p>Jl.Depok<br>Kel.Sukamenak<br>Kec.Purbaratu<br>Kota Tasikmalaya 46196</p>
          </div>

          <!-- Kontak Section -->
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h2 class="font-bold mb-2">Kontak</h2>
            <p> +62265312059<br>info@smkn4-tsm.sch.id</p>
          </div>

          <!-- Ikuti Kami Section -->
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h2 class="font-bold mb-2">Ikuti Kami</h2>
            <p><i class="fab fa-facebook"></i> Fans Page</p>
            <p><i class="fab fa-twitter"></i> Twitter</p>
            <p><i class="fab fa-instagram"></i> Instagram</p>
            <p><i class="fab fa-youtube"></i> Youtube</p>
          </div>

          <!-- Tautan Section -->
          <div class="w-full md:w-1/4 mb-6 md:mb-0">
            <h2 class="font-bold mb-2">Tautan</h2>
            <p>Kemdikbud</p>
            <p>Disdik Jabar</p>
            <p>Disdik Kota Tasikmalaya</p>
            <p>Belajar.id</p>
          </div>
        </div>

        <!-- Footer Bottom Section -->
        <div class="border-t border-white mt-6 pt-4 text-center">
          <p>©SMKN 4 Tasikmalaya. All rights reserved.</p>
        </div>
      </div>
    </footer>
</div>
</template>

<script>
export default {
  name: 'WelcomePage'
};
</script>

<style scoped>
/* Styling for footer */
.bg-green-600 {
  background-color: #338ba6e2;
}

.text-white {
  color: #ffffff;
}

.container {
  max-width: 1280px;
}

.text-center {
  text-align: center;
}

.font-bold {
  font-weight: 700;
}

.mb-2 {
  margin-bottom: 0.5rem;
}

.mb-6 {
  margin-bottom: 1.5rem;
}

.pt-4 {
  padding-top: 1rem;
}

.border-t {
  border-top-width: 1px;
}

.border-white {
  border-color: #ffffff;
}

/* Mengatur font dari h1 */
.h1 {
  font-family: "Abhaya Libre ExtraBold";
}
</style>

<style scoped>
/* Styling for footer */
.bg-green-600 {
  background-color: #338ba6e2;
}

.text-white {
  color: #ffffff;
}

.container {
  max-width: 1280px;
}

.text-center {
  text-align: center;
}

.font-bold {
  font-weight: 700;
}

.mb-2 {
  margin-bottom: 0.5rem;
}

.mb-6 {
  margin-bottom: 1.5rem;
}

.pt-4 {
  padding-top: 1rem;
}

.border-t {
  border-top-width: 1px;
}

.border-white {
  border-color: #ffffff;
}

/* Mengatur font dari h1 */
.h1 {
  font-family: "Abhaya Libre ExtraBold";
}

/* Mengatur gambar di carousel */
.carousel-content img {
  max-height: 600px;
  object-fit: cover; /* Menyesuaikan gambar tanpa mengubah aspek rasio */
  width: 100%; /* Pastikan gambar menyesuaikan lebar */
}

/* Membuat teks berada di tengah gambar */
.carousel-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%); /* Menempatkan teks di tengah */
  text-align: center;
  color: rgb(255, 255, 255);
  padding: 1rem;
  border-radius: 8px;
}

/* Styling untuk h1 dalam carousel */
.carousel-text h1 {
  font-size: 2rem;
  margin: 0;
}

/* Styling untuk p dalam carousel */
.carousel-text p {
  font-size: 1.2rem;
  margin: 0;
}

/* Styling Footer */
footer {
  background-color: #11419f79;
  padding: 20px 0;
  margin-top: 20px;
  text-align: center;
  width: 100%;
}

footer p {
  margin: 0;
  font-size: 0.875rem;
}

/* Menggunakan Flexbox untuk tata letak kolom footer */
.flex {
  display: flex;
  flex-wrap: wrap;
}

.w-full {
  width: 100%;
}

.md\:w-1\/4 {
  width: 25%; /* Setiap kolom akan mengambil lebar 25% pada layar medium ke atas */
}

.mb-6 {
  margin-bottom: 1.5rem; /* Memberikan jarak bawah antar elemen */
}

.md\:mb-0 {
  margin-bottom: 0; /* Menghilangkan margin pada layar besar */
}

@media (max-width: 768px) {
  .md\:w-1\/4 {
    width: 100%; /* Membuat elemen footer menjadi full width pada layar kecil */
  }
}
</style>