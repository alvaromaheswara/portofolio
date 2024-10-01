<script setup lang="ts"></script>

<template>
  <header class="py-6 bg-gradient-to-r from-blue-500 to-purple-500 shadow-lg">
    <nav class="container flex items-center justify-between">
      <!-- Navigation Links -->
      <ul class="flex gap-8 text-lg font-semibold text-white">
        <li>
          <NuxtLink
            to="/"
            class="hover:text-yellow-300 transition-all duration-300"
          >
            Home
          </NuxtLink>
        </li>
        <li>
          <a
            href="https://github.com/alvaromaheswara"
            target="_blank"
            class="hover:text-yellow-300 transition-all duration-300"
          >
            My Portfolio
          </a>
        </li>
        <li>
          <a
            href="https://www.instagram.com/alvaronugrho/"
            target="_blank"
            class="hover:text-yellow-300 transition-all duration-300"
          >
            Contact
          </a>
        </li>
      </ul>
    </nav>
  </header>
</template>

<style scoped>
header {
  font-family: 'Poppins', sans-serif;
}
a {
  transition: color 0.3s ease;
}
</style>