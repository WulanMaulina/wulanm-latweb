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

    <!-- Footer di bawah carousel -->
    <footer class="bg-gray-100 py-6 mt-10">
      <div class="container mx-auto text-center">
        <p class="text-gray-600">© 2024 SMK Negeri 4 Tasikmalaya. All Rights Reserved.</p>
      </div>
    </footer>
  </div>
</template>

<style scoped>
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
  background-color: rgba(0, 0, 0, 0.5); /* Background transparan untuk teks */
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

/* Styling footer */
footer {
  background-color: #11419f79;
  padding: 20px 0;
  margin-top: 20px;
  text-align: center;
}
</style>
