<template>
  <div class="welcome-page">
    <div id="carouselExampleSlidesOnly" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <div class="carousel-content">
            <img src="/assets/img/bacground.jpg" class="d-block w-100" alt="..." />
            <div class="carousel-text">
              <h1>Selamat Datang di Website Resmi</h1>
              <h1>SMK Negri 4 Tasikmalaya</h1>
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
    <div class="profile-page">
      <header class="bg-blue-800 text-white py-6">
        <div class="container mx-auto text-center">
          <h1 class="text-3xl font-bold">Profil SMK Negeri 4 Tasikmalaya</h1>
          <p class="text-lg mt-2">Visi dan Misi Kami</p>
        </div>
      </header>
      <div class="text-center">
        <h2 class="text-2xl font-semibold text-gray-800">Profil</h2>
      </div>
      <div class="text-center">
        <h3 class="text-2xl font-semibold text-gray-800">Sejarah SMK Negeri 4 Tasikmalayal</h3>
      </div>
      <main class="container mx-auto py-10 px-4">
        <section class="mb-8">
          <h2 class="text-2xl font-semibold text-gray-800">Visi</h2>
          <p class="mt-4 text-gray-700 leading-relaxed">“Menjadi sekolah unggul yang menghasilkan lulusan berkompeten, berkarakter, dan siap menghadapi tantangan global.”</p>
        </section>
        <section>
          <h2 class="text-2xl font-semibold text-gray-800">Misi</h2>
          <ul class="mt-4 text-gray-700 leading-relaxed list-disc pl-6">
            <li>Menyelenggarakan pendidikan berbasis teknologi dan informasi.</li>
            <li>Meningkatkan kualitas pembelajaran sesuai kebutuhan dunia kerja.</li>
            <li>Menanamkan nilai-nilai karakter pada seluruh peserta didik.</li>
            <li>Memperluas kerjasama dengan dunia usaha dan dunia industri.</li>
            <li>Menyiapkan lulusan yang memiliki jiwa kewirausahaan.</li>
          </ul>
        </section>
      </main>
      <footer class="bg-gray-100 py-6 mt-10">
        <div class="container mx-auto text-center">
          <p class="text-gray-600">© 2024 SMK Negeri 4 Tasikmalaya. All Rights Reserved.</p>
        </div>
      </footer>
    </div>
  </div>
</template>

<style scoped>
.h1 {
  font-family: "Abhaya Libre ExtraBold";
}
/* Mengatur tinggi maksimum gambar */
.carousel-content img {
  max-height: 600px;
  object-fit: cover; /* Menyesuaikan gambar tanpa mengubah aspek rasio */
}

/* Membuat teks berada di tengah */
.carousel-text {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  text-align: center;
  color: white;
  background-color: rgba(0, 0, 0, 0.5); /* Background transparan untuk teks */
  padding: 1rem;
  border-radius: 8px;
}

/* Styling tambahan untuk teks */
.carousel-text h1 {
  font-size: 2rem;
  margin: 0;
}

.carousel-text p {
  font-size: 1.2rem;
  margin: 0;
}
</style>
