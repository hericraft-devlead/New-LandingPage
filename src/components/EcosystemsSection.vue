<template>
  <section class="section2 w-full bg-white py-16 flex flex-col items-center text-center">
    <!-- Párrafo principal -->
    <p class="max-w-4xl text-2xl text-black mb-12 px-2 font-semibold">
      Ofrecemos <span>cuatro ecosistemas personalizados</span> que se adaptan a las
      instituciones, empresas y profesionistas para impulsar la <span>educación 5.0</span>
      según el perfil y las necesidades de cada cliente:
    </p>

    <!-- Cuatro imágenes -->
    <div class="flex flex-wrap justify-center gap-6 mb-16 px-6">
      <img src="../assets/img/c.png" alt="Ecosistema 1" class="w-56 h-56 object-cover" />
      <img src="../assets/img/a.png" alt="Ecosistema 2" class="w-56 h-56 object-cover" />
      <img src="../assets/img/m.png" alt="Ecosistema 3" class="w-56 h-56 object-cover" />
      <img src="../assets/img/p.png" alt="Ecosistema 4" class="w-56 h-56 object-cover" />
    </div>

    <!-- Texto adicional -->
    <h2 class="text-2xl font-semibold text-gray-800 mb-10">
      Además de nuestros <span>servicios adicionales</span>:
    </h2>

    <!-- Servicios adicionales -->
    <div class="flex flex-col md:flex-row justify-center items-start md:items-stretch gap-16 px-6 max-w-5xl">
      <!-- Servicio 1 -->
      <div class="flex-1 flex flex-col items-center text-center">
        <h3 class="text-2xl font-bold text-gray-800 mb-4">Visita nuestra<br><span>Tienda en línea</span></h3>

        <!-- Separador -->
        <div class="h-1 w-3/4 rounded-full mb-6"
             style="background: linear-gradient(90deg, rgba(59,130,246,0) 0%, rgba(59,130,246,1) 50%, rgba(59,130,246,0) 100%);">
        </div>

        <!-- Imagen debajo -->
        <img src="../assets/img/cart.png" alt="Consultoría personalizada" class="w-30 object-cover" />
      </div>

      <!-- Servicio 2 -->
      <div class="flex-1 flex flex-col items-center text-center">
        <h3 class="text-2xl font-bold text-gray-800 mb-4">Diseño y equipamiento <span>de Ambientes de Aprendizaje</span></h3>

        <!-- Separador -->
        <div class="h-1 w-3/4 rounded-full mb-6"
             style="background: linear-gradient(90deg, rgba(99,102,241,0) 0%, rgba(99,102,241,1) 50%, rgba(99,102,241,0) 100%);">
        </div>

        <!-- Imagen debajo -->
        <img src="../assets/img/env.png" alt="Desarrollo tecnológico" class="w-30 object-cover" />
      </div>
    </div>
  </section>
</template>
