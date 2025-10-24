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
        <div class="relative">
          <div class="recuadro-border absolute inset-0 m-4 rounded-4xl"></div>
          <div class="card bg-[#0b1224]/80 rounded-4xl flex flex-col items-center justify-start p-6 h-99 relative overflow-visible">

            <!-- Imagen superpuesta -->
            <img
              src="../assets/img/btn360.png"
              alt="Servicio 1"
              class="absolute -top-30 w-55 h-55 object-cover rounded-full"
            />

            <p class="cardcontent text-white text-center text-sm mt-20">
              <span class="cardtitle">Asesoría 360º<br></span>
              <span class="cardtext">y acompañamiento
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
        <div class="relative">
          <div class="recuadro-border absolute inset-0 m-4 rounded-4xl"></div>
          <div class="card rounded-4xl flex flex-col items-center justify-start p-6  h-99 relative overflow-visible">
            <img
              src="../assets/img/btninst.png"
              alt="Servicio 2"
              class="absolute -top-30 w-55 h-55 object-cover rounded-full"
            />
            <p class="cardcontent text-white text-center text-sm mt-20">
              <span class="cardtitle">Instituciones educativas<br><br></span>
              Ofrecemos licencias escolares completas a las instituciones educativas.
            </p>
          </div>
        </div>

        <!-- Tarjeta 3 -->
        <div class="relative">
          <div class="recuadro-border absolute inset-0 m-4 rounded-4xl"></div>
          <div class="card rounded-4xl flex flex-col items-center justify-start p-6  h-99 relative overflow-visible">
            <img
              src="../assets/img/btnprof.png"
              alt="Servicio 3"
              class="absolute -top-30 w-55 h-55 object-cover rounded-full"
            />
            <p class="cardcontent text-white text-center text-sm mt-20">
              <span class="cardtitle">Profesionistas<br><br></span>
              Brindamos acceso a contenidos personalizados para grupos de profesionistas.
            </p>
          </div>
        </div>

        <!-- Tarjeta 4 -->
        <div class="relative">
          <div class="recuadro-border absolute inset-0 m-4 rounded-4xl"></div>
          <div class="card rounded-4xl flex flex-col items-center justify-start p-6  h-99 relative overflow-visible">
            <img
              src="../assets/img/btnempr.png"
              alt="Servicio 4"
              class="absolute -top-30 w-55 h-55 object-cover rounded-full"
            />
            <p class="cardcontent text-white text-center text-sm mt-20">
              <span class="cardtitle">Empresas<br><br></span>
              Una plataforma integral de formación y gestión del aprendizaje a empresas.
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
