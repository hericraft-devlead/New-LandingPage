<template>
  <header class="navbar w-full fixed top-0 left-0 z-50 bg-transparent">
    <div>
      <nav
        class="flex justify-between items-center gap-8 text-sm font-semibold px-6 md:px-12"
      >
        <!-- Logo -->
        <div class="flex items-center space-x-5">
          <img src="../assets/logo.png" alt="Logo" class="h-10 w-auto" />
        </div>

        <!-- Menú hamburguesa (visible solo en móviles) -->
        <button
          @click="isOpen = !isOpen"
          class="md:hidden text-white focus:outline-none"
        >
          <svg
            v-if="!isOpen"
            xmlns="http://www.w3.org/2000/svg"
            class="h-7 w-7"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M4 6h16M4 12h16M4 18h16" />
          </svg>
          <svg
            v-else
            xmlns="http://www.w3.org/2000/svg"
            class="h-7 w-7"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
              d="M6 18L18 6M6 6l12 12" />
          </svg>
        </button>

        <!-- Menú principal -->
        <ul
          class="hidden md:flex space-x-10 text-white font-medium"
        >
          <li><a href="#home" class="text-teal-300 pb-2 relative after:content-[''] after:absolute after:bottom-0 after:left-0 after:w-full after:h-[3px] after:bg-gradient-to-r after:from-teal-300 after:to-cyan-400">INICIO</a></li>
          <li><a href="#about" class="text-white hover:text-cyan-400 transition">NOSOTROS</a></li>
          <li><a href="#college" class=" text-white hover:text-cyan-400 transition">COLLEGE</a></li>
          <li><a href="#agora" class="text-white hover:text-cyan-400 transition">ÁGORA</a></li>
          <li><a href="#metanoia" class="text-white hover:text-cyan-400 transition">METANOIA</a></li>
          <li><a href="#procesus" class="text-white hover:text-cyan-400 transition">PROCESSUS</a></li>
        </ul>

        <!-- Botón -->
        <a
          href="#login"
          class="hidden md:inline-block px-6 py-2 bg-gray-100 text-sm font-bold text-black rounded-lg shadow-lg hover:scale-110 transition-transform"
        >
          INICIAR SESIÓN
        </a>
      </nav>

      <!-- Menú desplegable móvil -->
      <transition name="fade">
        <div
          v-if="isOpen"
          class="md:hidden bg-black/90 text-white flex flex-col items-center py-6 space-y-4 font-medium"
        >
          <a href="#home" @click="isOpen = false">INICIO</a>
          <a href="#about" @click="isOpen = false">NOSOTROS</a>
          <a href="#college" @click="isOpen = false">COLLEGE</a>
          <a href="#agora" @click="isOpen = false">ÁGORA</a>
          <a href="#metanoia" @click="isOpen = false">METANOIA</a>
          <a href="#procesus" @click="isOpen = false">PROCESSUS</a>

          <!-- Botón en versión móvil -->
          <a
            href="#login"
            class="px-6 py-2 bg-gray-100 text-black rounded-lg shadow-lg hover:scale-105 transition-transform"
            @click="isOpen = false"
          >
            INICIAR SESIÓN
          </a>
        </div>
      </transition>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(false)
</script>

<style scoped>
.fade-enter-active,
.fade-leave-active {
  transition: opacity 0.3s ease;
}
.fade-enter-from,
.fade-leave-to {
  opacity: 0;
}
</style>
