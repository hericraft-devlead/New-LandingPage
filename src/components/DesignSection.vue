<template>
  <section class="section3 w-full bg-gray-500 py-20 overflow-hidden">
    <!-- Contenedor general -->
    <div class="w-full">

        <!-- Textos superiores -->
<div class="w-full px-8 md:px-16 mb-16">
  <h2 class="text-2xl md:text-4xl mb-6 text-left">
    <span>Diseño educativo <br>según tus necesidades</span>
  </h2>
  <h3 class="text-3xl md:text-2xl font-bold text-white mb-16 text-left">
    En Hericraft personalizamos cada experiencia de aprendizaje <br>según el perfil, contexto y necesidades de nuestros clientes.
  </h3>
</div>

<!-- Rectángulo alineado al borde derecho -->
<div class="w-full flex justify-end pr-0 md:pr-0">
  <div class="rectangulo md:text-3xl text-white px-18 py-4 rounded-l-2xl text-right max-w-5xl mb-35 font-medium">
    Integramos metodologías activas, tecnología y ambientes <br>
    que transforman la experiencia formativa.
  </div>
</div>

      <!-- Cuatro recuadros -->
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 px-8 md:px-16 mb-20">
        <!-- Tarjeta 1 -->
        <div class="rounded-2xl p-[3px]" style="background: linear-gradient(135deg, rgba(34,211,238,0.8), rgba(59,130,246,0.8));">
          <div class="card rounded-2xl flex flex-col items-center justify-end p-6 h-64 relative overflow-visible">

            <!-- Imagen superpuesta -->
            <img
              src=""
              alt="Servicio 1"
              class="absolute -top-20 w-32 h-32 object-cover rounded-full border-4 border-gray-900 shadow-lg"
            />

            <p class="text-white text-center text-sm mt-20">
              <span>Asesoría 360º<br>
              y acompañamiento
              continuo <br><br></span>
              Cada cliente cuenta con
              un asesor experto que guía
              todo el proceso, desde la
              estrategia educativa hasta
              la implementación
              tecnológica.
            </p>
          </div>
        </div>

        <!-- Tarjeta 2 -->
        <div class="relative bg-transparent rounded-2xl p-[3px]"
             style="background: linear-gradient(135deg, rgba(34,211,238,0.8), rgba(59,130,246,0.8));">
          <div class="card rounded-2xl flex flex-col items-center justify-end p-6 h-64 relative overflow-visible">
            <img
              src=""
              alt="Servicio 2"
              class="absolute -top-20 w-32 h-32 object-cover rounded-full border-4 border-gray-900 shadow-lg"
            />
            <p class="text-white text-center text-sm mt-20">
              Integración de tecnología educativa
            </p>
          </div>
        </div>

        <!-- Tarjeta 3 -->
        <div class="relative bg-transparent rounded-2xl p-[3px]"
             style="background: linear-gradient(135deg, rgba(34,211,238,0.8), rgba(59,130,246,0.8));">
          <div class="card rounded-2xl flex flex-col items-center justify-end p-6 h-64 relative overflow-visible">
            <img
              src=""
              alt="Servicio 3"
              class="absolute -top-20 w-32 h-32 object-cover rounded-full border-4 border-gray-900 shadow-lg"
            />
            <p class="text-white text-center text-sm mt-20">
              Capacitación docente especializada
            </p>
          </div>
        </div>

        <!-- Tarjeta 4 -->
        <div class="relative bg-transparent rounded-2xl p-[3px]"
             style="background: linear-gradient(135deg, rgba(34,211,238,0.8), rgba(59,130,246,0.8));">
          <div class="card rounded-2xl flex flex-col items-center justify-end p-6 h-64 relative overflow-visible">
            <img
              src=""
              alt="Servicio 4"
              class="absolute -top-20 w-32 h-32 object-cover rounded-full border-4 border-gray-900 shadow-lg"
            />
            <p class="text-white text-center text-sm mt-20">
              Evaluación y mejora continua
            </p>
          </div>
        </div>
      </div>

      <!-- Botón inferior -->
      <div class="flex justify-center mt-12">
        <div class="relative inline-block">
            <!-- Imagen sobresaliente -->
            <img
            src="../assets/img/contact.png"
            alt="Ícono contacto"
            class="absolute -left-10 top-1/2 -translate-y-1/2 w-23 h-23"
            />

            <!-- Botón -->
            <button class="flex justify-end items-center pl-20 pr-10 py-4 rounded-3xl hover:scale-105 transition-transform shadow-lg">
              Contáctanos y conoce más
            </button>
        </div>
        </div>
    </div>
  </section>
</template>
