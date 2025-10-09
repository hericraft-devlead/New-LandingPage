<template>
    <footer class="bg-gray-900 text-white py-16 relative overflow-hidden">
        <div class="container mx-auto px-8 flex flex-col md:flex-row justify-between items-start md:items-center mb-16">
            <!-- Texto de misión -->
            <div class="max-w-xl">
            <p class="text-lg leading-relaxed relative">
                <span class="absolute -left-6 -top-6 text-6xl font-bold bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text text-transparent select-none">“</span>
                Nuestra misión es ser la solución integral a las necesidades 
                que demanda la nueva manera de aprendizaje,<br>
                apoyando a las instituciones en las implementaciones
                de diferentes metodologías de aprendizaje.
            </p>
            </div>

            <!-- Íconos de redes -->
            <div class="flex gap-4 mt-10 md:mt-0">
            <!-- Cada botón -->
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-facebook-f text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-instagram text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-x-twitter text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-linkedin-in text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-youtube text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-tiktok text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            <button class="w-10 h-10 rounded-full bg-gray-800 shadow-md shadow-gray-700 flex items-center justify-center hover:scale-105 transition-transform">
                <i class="fa-brands fa-whatsapp text-transparent bg-gradient-to-r from-cyan-400 to-blue-500 bg-clip-text"></i>
            </button>
            </div>
        </div>

        <!-- Navbar inferior -->
        <div class="border-t border-gray-700/50 pt-6">
            <nav class="flex justify-center gap-8 text-sm font-semibold mb-4 relative">
            <a href="#" class="text-cyan-400 pb-2 relative after:content-[''] after:absolute after:bottom-0 after:left-0 after:w-full after:h-[2px] after:bg-gradient-to-r after:from-cyan-400 after:to-blue-500">Inicio</a>
            <a href="#" class="text-gray-400 hover:text-white transition">Nosotros</a>
            <a href="#" class="text-gray-400 hover:text-white transition">Servicios</a>
            <a href="#" class="text-gray-400 hover:text-white transition">Proyectos</a>
            <a href="#" class="text-gray-400 hover:text-white transition">Blog</a>
            <a href="#" class="text-gray-400 hover:text-white transition">Contacto</a>
            </nav>

            <!-- Derechos reservados -->
            <p class="text-center text-gray-500 text-xs">
            © 2025 <span class="font-semibold text-white">Hericraft</span>. Todos los derechos reservados.
            </p>
        </div>
    </footer>
</template>