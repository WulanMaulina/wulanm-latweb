<template>
  <div class="welcome-page">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="carousel-content">
            <img src="/assets/img/bacground.jpg" class="d-block w-100" alt="..." />
            <div class="carousel-text">
              <h1>Selamat Datang di Website Resmi</h1>
              <h1>SMK Negeri 4 Tasikmalaya</h1>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="carousel-content">
            <img src="..." class="d-block w-100" alt="..." />
            <div class="carousel-text">
              <h1>Judul Slide 2</h1>
              <p>Deskripsi slide 2</p>
            </div>
          </div>
        </div>
        <div class="carousel-item">
          <div class="carousel-content">
            <img src="..." class="d-block w-100" alt="..." />
            <div class="carousel-text">
              <h1>Judul Slide 3</h1>
              <p>Deskripsi slide 3</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>



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



