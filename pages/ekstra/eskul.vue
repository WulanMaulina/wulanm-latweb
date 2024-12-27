<template>
  <div class="bg-gray-100 py-8 body">
    <div class="container mx-auto p-4">
      <h1 class="text-3xl font-bold mb-4 text-center text-gray-900">Ekskul</h1>
      <p class="text-gray-600 mb-8 text-center">Ekstrakurikuler Sekolah</p>
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <div v-for="activity in activities" :key="activity.title" class="bg-white rounded-lg shadow-lg overflow-hidden">
          <!-- Image with Text Overlay -->
          <div class="relative">
            <img :src="activity.image" :alt="activity.title" class="w-full h-36 object-cover" />
            <!-- Ukuran gambar lebih kecil -->
            <div class="absolute inset-0 bg-black opacity-50"></div>
            <!-- Menambah kontras -->
            <div class="absolute inset-0 flex items-center justify-center text-dark text-center p-4">
              <div>
                <h2 class="text-2xl teks-center font-semibold">{{ activity.title }}</h2>
                <p class="mt-2 text-lg">{{ activity.description }}</p>
                <!-- Ukuran teks lebih besar -->
              </div>
            </div>
          </div>

          <!-- Content under the image -->
          <div class="p-6">
            <div class="flex items-center mb-4">
              <i class="fas fa-user text-orange-500 mr-2"></i>
              <span class="text-gray-700 font-semibold">{{ activity.creator }}</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      activities: [
        {
          title: "Pencak Silat",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
        {
          title: "Paduan Suara",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
        {
          title: "Kerohanian",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
        {
          title: "Badminton",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
        {
          title: "Pramuka",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
        {
          title: "Seni",
          image: "https://images.bisnis.com/posts/2023/11/14/1714300/pramuka_1_1699953189.jpeg",
        },
      ],
    };
  },
};
</script>

<style scoped>
.body {
  margin-top: 50px;
}
/* Styling untuk tampilan yang lebih bersih dan rapi */
.bg-gray-100 {
  background-color: #4298cd99;
}

.container {
  max-width: 1280px;
}

.text-center {
  text-align: center;
}

.text-white {
  color: #0c0c0c;
}

.relative {
  position: relative;
}

.absolute {
  position: absolute;
}

.bg-black {
  background-color: #000;
}

.opacity-50 {
  /* Menambah kontras dengan opacity 50% */
  opacity: 0.5;
}

.w-full {
  width: 100%;
}

.mt-4 {
  margin-top: 1rem;
}

button {
  font-weight: 600;
}

button:hover {
  background-color: #4b5563;
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
}

button {
  transition: background-color 0.3s ease;
}

/* Styling tambahan untuk jarak antar elemen */
.py-8 {
  padding-top: 2rem;
  padding-bottom: 2rem;
}

.gap-8 {
  gap: 2rem;
}

.p-4 {
  padding: 1rem;
}

.p-6 {
  padding: 1.5rem;
}

.mb-8 {
  margin-bottom: 2rem;
}

.mb-4 {
  margin-bottom: 1rem;
}

.mt-2 {
  margin-top: 0.5rem;
}

/* Menambah ukuran font untuk deskripsi */
.text-lg {
  font-size: 1.125rem; /* 18px */
}

/* Flexbox tambahan untuk memusatkan konten teks */
.relative .absolute {
  display: flex;
  justify-content: center;
  align-items: center;
}
</style>
