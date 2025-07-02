<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Frescura Vital</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-green-50 text-gray-800 font-sans">
  <!-- Header -->
  <header class="bg-green-700 text-white p-6">
    <div class="max-w-5xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Frescura Vital</h1>
      <nav class="space-x-4">
        <a href="#beneficios" class="hover:underline">Beneficios</a>
        <a href="#criticas" class="hover:underline">Críticas</a>
        <a href="#contacto" class="hover:underline">Contacto</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-5xl mx-auto p-8 text-center">
    <h2 class="text-4xl font-bold mb-4">Bienvenido a Frescura Vital</h2>
    <p class="mb-6 text-lg">Explora los beneficios de usar desodorantes naturales y conoce opiniones constructivas para mejorar su uso y desarrollo.</p>
    <a href="#beneficios" class="bg-green-700 text-white px-6 py-3 rounded-full hover:bg-green-800">Descubrir</a>
  </section>

  <!-- Beneficios -->
  <section id="beneficios" class="bg-white py-12">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6 text-center">Beneficios del Desodorante Natural</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Libre de químicos tóxicos</h3>
          <p>Formulado sin aluminio ni parabenos, protege tu piel de irritaciones y alergias.</p>
        </div>
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Respeta la transpiración</h3>
          <p>Permite la transpiración natural del cuerpo, evitando obstruir los poros.</p>
        </div>
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Amigable con el ambiente</h3>
          <p>Ingredientes biodegradables y empaques reutilizables que reducen el impacto ambiental.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Críticas Constructivas -->
  <section id="criticas" class="bg-green-100 py-12">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6 text-center">Críticas Constructivas</h2>
      <ul class="space-y-6">
        <li class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Duración limitada</h3>
          <p>Algunos usuarios notan que la protección del desodorante natural puede durar menos que los convencionales, por lo que se recomienda reaplicar durante el día.</p>
        </li>
        <li class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Adaptación de la piel</h3>
          <p>Es posible que al cambiar a un desodorante natural, la piel necesite un período de ajuste mientras elimina toxinas acumuladas.</p>
        </li>
        <li class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Precio más alto</h3>
          <p>Generalmente, los desodorantes naturales pueden ser más costosos debido a la calidad de los ingredientes orgánicos.</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="max-w-5xl mx-auto p-8 text-center">
    <h2 class="text-3xl font-bold mb-4">Contáctanos</h2>
    <p class="mb-6">¿Tienes sugerencias o quieres compartir tu experiencia? Escríbenos.</p>
    <form class="max-w-md mx-auto">
      <input type="text" placeholder="Nombre" class="w-full p-3 mb-4 border border-gray-300 rounded" required />
      <input type="email" placeholder="Correo Electrónico" class="w-full p-3 mb-4 border border-gray-300 rounded" required />
      <textarea placeholder="Mensaje" class="w-full p-3 mb-4 border border-gray-300 rounded" rows="4" required></textarea>
      <button type="submit" class="bg-green-700 text-white px-6 py-3 rounded hover:bg-green-800">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-700 text-white text-center p-4">
    <p>&copy; 2025 Frescura Vital. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
