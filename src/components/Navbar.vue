<template>
  <header class="w-full bg-gray shadow-md">
    <nav class="w-full flex justify-between items-center px-6 py-4">
      <!-- Logo -->
      <div class="flex items-center space-x-5">
        <img src="../assets/logo.png" alt="Logo" class="h-10 w-30" />
      </div>

      <!-- Links -->
      <ul class="hidden md:flex space-x-6 text-gray-700 font-medium">
        <li><a href="#about" class="hover:text-blue-600">Inicio</a></li>
        <li><a href="#services" class="hover:text-blue-600">Nosotros</a></li>
        <li><a href="#pricing" class="hover:text-blue-600">College</a></li>
        <li><a href="#team" class="hover:text-blue-600">Ágora</a></li>
        <li><a href="#contact" class="hover:text-blue-600">Metanoia</a></li>
        <li><a href="#faq" class="hover:text-blue-600">Processus</a></li>
      </ul>

      <!-- Botón -->
      <a
        href="#login"
        class="ml-6 px-4 py-2 bg-gray-100 text-black rounded-lg hover:bg-blue-700"
      >
        Iniciar sesión
      </a>
    </nav>
  </header>
</template>
