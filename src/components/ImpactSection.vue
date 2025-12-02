<template>
<section class="section4 relative overflow-hidden">
  <div class="container mx-auto px-6">

    <!-- Bloque 1: imagen izquierda -->
    <div class="flex flex-col md:flex-row items-center md:items-start mb-20">
      <img
        src="../assets/img/instituciones.png"
        alt="Instituciones"
        class="w-40 md:w-35 mb-6 md:mb-0 md:mr-3 ml-4 md:ml-8"
      />
      <p class="text-white font-bold text-2xl md:text-3xl">
        <span class="text-5xl md:text-6xl font-extrabold mr-2">+35</span>
        instituciones educativas
      </p>
    </div>

    <!-- Bloque 2: imagen derecha -->
    <div class="flex flex-col md:flex-row-reverse items-center md:items-start mb-20">
      <img
        src="../assets/img/usuarios.png"
        alt="Alianzas"
        class="w-40 md:w-35 mb-6 md:mb-0 md:ml-8 mr-4 md:ml-8"
      />
      <p class="text-white font-bold text-2xl md:text-3xl text-right md:text-left">
        <span class="text-5xl md:text-6xl font-extrabold mr-2">+5000</span>
        usuarios
      </p>
    </div>

    <!-- Bloque 3: imagen izquierda -->
    <div class="flex flex-col md:flex-row items-center md:items-start mb-28">
      <img
        src="../assets/img/experiencia.png"
        alt="Experiencia"
        class="w-40 md:w-35 mb-6 md:mb-0 md:mr-8 ml-4 md:ml-8"
      />
      <p class="text-white font-bold text-2xl md:text-3xl">
        <span class="text-5xl md:text-6xl font-extrabold mr-2">3</span>
        organizaciones capacitadas
      </p>
    </div>

    <!-- Rectángulo central -->
    <div class="flex justify-center">
      <div
        class="bg-gray-300 rounded-t-3xl px-10 py-8 text-center w-full max-w-4xl shadow-xl relative"
      >
        <div class="flex flex-col md:flex-row items-center justify-center gap-4">
          <img src="../assets/img/expertos.png" alt="Expertos" class="w-20 h-20" />
          <p class="text-gray-900 font-bold text-xl md:text-2xl">
            <span class="text-5xl md:text-6xl font-extrabold mr-2">+12</span>
            expertos en EdTech, diseño y educación.
          </p>
        </div>

        <!-- Separador degradado -->
        <div
          class="absolute left-1/2 -translate-x-1/2 bottom-0 translate-y-1/2 w-[150%] h-2 bg-gradient-to-r from-transparent via-teal-300"
        ></div>
      </div>
    </div>

  </div>
</section>
</template>
