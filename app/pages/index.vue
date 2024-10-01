<script lang="ts" setup></script>

<template>
  <main>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">

   <!-- Section Tentang Saya -->
   <section class="bg-gradient-to-r from-indigo-500 to-purple-500 text-white py-20">
     <div class="container flex flex-col items-center space-y-10 lg:space-y-0">
       <!-- Image (Top Column) -->
       <div class="flex-1 order-1">
         <NuxtImg
           sizes="xs:100vw sm:350px"
           src="profil.jpeg"
           format="webp"
           densities="x1"
           alt="Foto Wafa"
           class="w-40 h-40 lg:w-52 lg:h-52 rounded-full shadow-2xl transform hover:scale-105 transition-transform duration-500"
         />
       </div>

       <!-- Text (Bottom Column) -->
       <div class="p-10 flex-1 order-2 text-center space-y-6">
         <h1 class="text-5xl lg:text-6xl font-extrabold leading-tight">
          <span>Alvaro Maheswara Nugroho</span>
         </h1>
         <p class="text-2xl lg:text-3xl">Software Engineer</p>
       </div>
     </div>
   </section>

   <section class="py-16 bg-gradient-to-r from-indigo-400 to-purple-400 text-white">
    <div class="max-w-4xl mx-auto px-4">
      <h2 class="text-4xl font-semibold text-center mb-12">Ketrampilan</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
        <div
        class="bg-gradient-to-br from-yellow-400 to-yellow-500 p-6 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-2 transition-all duration-300">
          <NuxtImg 
            src="java-icon.svg" 
            alt="Vue" 
            class="w-12 h-12 mx-auto mb-4" 
          />
          <p class="text-xl font-semibold text-white">Java</p>
        </div>
        <div
        class="bg-gradient-to-br from-pink-400 to-pink-500 p-6 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-2 transition-all duration-300">
          <NuxtImg 
            src="C++-icon.svg" 
            alt="HTML" 
            class="w-12 h-12 mx-auto mb-4" 
          />
          <p class="text-xl font-semibold text-white">C++</p>
        </div>
        <div
          class="bg-gradient-to-br from-blue-400 to-blue-500 p-6 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-2 transition-all duration-300">
          <NuxtImg 
            src="figma-icon.svg" 
            alt="Flutter" 
            class="w-12 h-12 mx-auto mb-4" 
          />
          <p class="text-xl font-semibold text-white">Figma</p>
        </div>
        <div
        class="bg-gradient-to-br from-green-400 to-green-500 p-6 rounded-lg shadow-lg hover:shadow-xl transform hover:-translate-y-2 transition-all duration-300">
          <NuxtImg 
            src="html-icon.svg" 
            alt="Java" 
            class="w-12 h-12 mx-auto mb-4" 
          />
          <p class="text-xl font-semibold text-white">HTML</p>
        </div>
      </div>
    </div>
   </section>


    <!-- Section Pengalaman -->
    <section class="py-20 bg-gradient-to-r from-indigo-300 to-purple-300 text-white">
  <div class="max-w-6xl mx-auto text-center px-4">
    <h2 class="text-4xl font-semibold mb-10">Riwayat Pendidikan</h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-12">
      <!-- Sidigs Experience -->
      <div class="experience-item relative group bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-lg shadow-lg hover:shadow-2xl transition-all duration-500">
        <NuxtImg
          sizes="xs:100vw sm:350px"
          src="smp.png"
          format="webp"
          densities="x1"
          alt="Telkom DBT"
          class="mb-6 w-full rounded-lg transform group-hover:scale-105 transition-transform duration-500"
        />
        <h3 class="text-2xl font-bold mb-4 group-hover:text-blue-600 transition-colors duration-300">
          SMP Muhammadiyah 1 Sidoarjo
        </h3>
        <div class="absolute top-0 left-0 w-full h-full rounded-lg bg-blue-500 opacity-0 group-hover:opacity-10 transition-opacity duration-500"></div>
      </div>
      
      <!-- Telkom DBT Experience -->
      <div class="experience-item relative group bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-lg shadow-lg hover:shadow-2xl transition-all duration-500">
        <NuxtImg
          sizes="xs:100vw sm:350px"
          src="sma.png"
          format="webp"
          densities="x1"
          alt="Telkom DBT"
          class="mb-6 w-full rounded-lg transform group-hover:scale-105 transition-transform duration-500"
        />
        <h3 class="text-2xl font-bold mb-4 group-hover:text-blue-600 transition-colors duration-300">
          SMAN 1 Sidoarjo
        </h3>
        <div class="absolute top-0 left-0 w-full h-full rounded-lg bg-blue-500 opacity-0 group-hover:opacity-10 transition-opacity duration-500"></div>
      </div>
      <div class="experience-item relative group bg-gradient-to-br from-blue-50 to-blue-100 p-8 rounded-lg shadow-lg hover:shadow-2xl transition-all duration-500">
        <NuxtImg
          sizes="xs:100vw sm:350px"
          src="ub.jpeg"
          format="webp"
          densities="x1"
          alt="Telkom DBT"
          class="mb-6 w-full rounded-lg transform group-hover:scale-105 transition-transform duration-500"
        />
        <h3 class="text-2xl font-bold mb-4 group-hover:text-blue-600 transition-colors duration-300">
          Universitas Brawijaya
        </h3>
        <div class="absolute top-0 left-0 w-full h-full rounded-lg bg-blue-500 opacity-0 group-hover:opacity-10 transition-opacity duration-500"></div>
      </div>
    </div>
  </div>
</section>

<footer class="bg-gradient-to-r from-indigo-500 to-purple-500 text-white py-12">
      <div class="container mx-auto text-center">
        <div class="flex justify-center space-x-4 mb-6">
          <a href="https://github.com/alvaromaheswara" target="_blank" class="hover:text-yellow-400">
            <i class="fab fa-github fa-2x"></i>
          </a>
          <a href="/" target="_blank" class="hover:text-yellow-400">
            <i class="fab fa-linkedin fa-2x"></i>
          </a>
          <a href="mailto:alvaronugroho@student.ub.ac.id" class="hover:text-yellow-400">
            <i class="fas fa-envelope fa-2x"></i>
          </a>
        </div>
        <p class="text-lg font-medium">&copy; 2024 Alvaro | All rights reserved.</p>
      </div>
    </footer>

  </main>
</template>

<style scoped>
h2, h3 {
  font-family: 'Poppins', sans-serif;
}

.experience-item {
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.experience-item:hover {
  transform: translateY(-10px);
}

footer i {
  transition: color 0.3s ease;
}
</style>
