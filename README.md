<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Frescura Vital</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-green-50 text-gray-800 font-sans">
  <!-- Header -->
  <header class="bg-green-600 text-white p-6">
    <div class="max-w-5xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Frescura Vital</h1>
      <nav class="space-x-4">
        <a href="#inicio" class="hover:underline">Inicio</a>
        <a href="#productos" class="hover:underline">Productos</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section id="inicio" class="max-w-5xl mx-auto p-8 text-center">
    <h2 class="text-4xl font-bold mb-4">Siente la frescura de lo natural</h2>
    <p class="mb-6">Descubre nuestra línea de productos naturales para tu bienestar diario.</p>
    <a href="#productos" class="bg-green-600 text-white px-6 py-3 rounded-full hover:bg-green-700">Ver Productos</a>
  </section>

  <!-- Productos -->
  <section id="productos" class="bg-white py-12">
    <div class="max-w-5xl mx-auto text-center">
      <h2 class="text-3xl font-bold mb-8">Nuestros Productos</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="bg-green-100 p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Desodorante Natural</h3>
          <p class="mb-4">Libre de químicos, suave con tu piel y efectivo todo el día.</p>
          <button class="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">Comprar</button>
        </div>
        <div class="bg-green-100 p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Spray Refrescante</h3>
          <p class="mb-4">Mantente fresco con ingredientes 100% orgánicos.</p>
          <button class="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">Comprar</button>
        </div>
        <div class="bg-green-100 p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Bálsamo Calmante</h3>
          <p class="mb-4">Ideal para después del afeitado o piel irritada.</p>
          <button class="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">Comprar</button>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="max-w-5xl mx-auto p-8 text-center">
    <h2 class="text-3xl font-bold mb-4">Contáctanos</h2>
    <p class="mb-6">¿Tienes preguntas? Escríbenos y te responderemos pronto.</p>
    <form class="max-w-md mx-auto">
      <input type="text" placeholder="Nombre" class="w-full p-3 mb-4 border border-gray-300 rounded" required/>
      <input type="email" placeholder="Correo Electrónico" class="w-full p-3 mb-4 border border-gray-300 rounded" required/>
      <textarea placeholder="Mensaje" class="w-full p-3 mb-4 border border-gray-300 rounded" rows="4" required></textarea>
      <button type="submit" class="bg-green-600 text-white px-6 py-3 rounded hover:bg-green-700">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-600 text-white text-center p-4">
    <p>&copy; 2025 Frescura Vital. Todos los derechos reservados.</p>
  </footer>
</body>
</html>

