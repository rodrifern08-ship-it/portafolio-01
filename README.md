# portafolio-01
<!DOCTYPE1 html>
<html lang="es" class="dark">
<head>
  <meta charset="UTF-8">
  <title>Mi Portafolio Dashboard</title>
  <!-- CDN de Tailwind CSS para prototipar rápido -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-[#121212] text-white flex h-screen font-sans">

  <!-- 1. Menú Lateral (Sidebar) -->
  <aside class="w-64 bg-[#1e1e1e] border-r border-gray-800 p-4 flex flex-col gap-4">
    <h1 class="font-bold text-lg px-2">Mi Dashboard</h1>
    <nav class="flex flex-col gap-2">
      <a href="#" class="p-2 rounded-lg bg-gray-800 text-white font-medium">Inicio / Perfil</a>
      <a href="#" class="p-2 rounded-lg text-gray-400 hover:bg-gray-800">Currículum</a>
      <a href="#" class="p-2 rounded-lg text-gray-400 hover:bg-gray-800">Galería / Proyectos</a>
    </nav>
  </aside>

  <!-- 2. Contenido Principal -->
  <main class="flex-1 p-8 overflow-y-auto">
    <!-- Encabezado y Barra de progreso -->
    <div class="bg-[#1e1e1e] border border-gray-800 rounded-xl p-6 mb-6">
      <div class="flex justify-between items-center mb-4">
        <h2 class="text-xl font-bold">Completitud del Perfil</h2>
        <span class="text-orange-500 font-bold text-xl">100%</span>
      </div>
      <!-- Barra de progreso -->
      <div class="w-full bg-gray-700 h-2.5 rounded-full overflow-hidden">
        <div class="bg-orange-500 h-2.5 rounded-full w-full"></div>
      </div>
    </div>

    <!-- 3. Sección de Galería / Mídia -->
    <div class="bg-[#1e1e1e] border border-gray-800 rounded-xl p-6">
      <h3 class="text-lg font-bold mb-4">Galería de Proyectos / Trabajo</h3>
      <div class="grid grid-cols-4 gap-4">
        <img src="https://via.placeholder.com/150" class="rounded-lg object-cover w-full h-32">
        <img src="https://via.placeholder.com/150" class="rounded-lg object-cover w-full h-32">
        <div class="border-2 border-dashed border-gray-700 rounded-lg flex items-center justify-center text-gray-500 cursor-pointer">
          + Añadir más
        </div>
      </div>
    </div>
  </main>

</body>
</html>
