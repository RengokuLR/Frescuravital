<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Frescura Vital</title>
  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-green-50 text-green-900 font-sans">
  <!-- Encabezado -->
  <header class="bg-green-800 text-white p-6">
    <div class="max-w-5xl mx-auto flex justify-between items-center">
      <h1 class="text-3xl font-bold">Frescura Vital</h1>
      <nav class="space-x-4">
        <a href="#beneficios" class="hover:underline">Beneficios</a>
        <a href="#criticas" class="hover:underline">Críticas</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-5xl mx-auto p-8 text-center">
    <img src="https://th.bing.com/th/id/R.c68dccfd62c690089b1fe71ba3819bfb?rik=RnwRuSxu3RpEfg&pid=ImgRaw&r=0/1200x400/?nature,animals" alt="Imagen Naturaleza Animalista" class="w-full h-64 object-cover rounded-lg mb-6">
    <h2 class="text-4xl font-bold mb-4">Bienvenido a Frescura Vital</h2>
    <p class="mb-6 text-lg">Cuidamos tu piel y respetamos la naturaleza y la vida animal. Descubre cómo un desodorante natural puede marcar la diferencia.</p>
    <a href="#beneficios" class="bg-green-800 text-white px-6 py-3 rounded-full hover:bg-green-900">Descubrir</a>
  </section>

  <!-- Beneficios -->
  <section id="beneficios" class="bg-beige-50 py-12">
    <div class="max-w-5xl mx-auto px-6">
      <h2 class="text-3xl font-bold mb-6 text-center">Beneficios del Desodorante Natural</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <img src="https://thumbs.dreamstime.com/b/colorful-non-toxic-sign-concept-regulations-ecology-vector-illustration-268216133.jpg/300x200/?plant,nature" alt="Beneficio 1" class="w-full h-40 object-cover rounded mb-4">
          <h3 class="text-xl font-bold mb-2">Sin químicos tóxicos</h3>
          <p>Libre de ingredientes dañinos para ti y para los ecosistemas.</p>
        </div>
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <img src="https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgVPxUVmYDFp4ntw15M9d64gy6HJF89YVNMWCwc5qkQUwzsAsl5cT1S9sDiYjqn438UYf7UW3wwfh6_7dOTr7nuEYYkcjbZYrpsPmQwLskU-lJd2TKdsYcx7KNosW-LA98GlA5T7qB8uuUcg1zOW84A6RJcYfUP1eFxLXx6c7wrFKMKONZqisBGUm91B9Zp/s1080/a23053_8fc4d85bffdb404d973c9217a266b669~mv2.gif/300x200/?organic,forest" alt="Beneficio 2" class="w-full h-40 object-cover rounded mb-4">
          <h3 class="text-xl font-bold mb-2">Respeta tu cuerpo</h3>
          <p>Permite transpirar de forma natural sin tapar poros ni alterar procesos vitales.</p>
        </div>
        <div class="p-6 bg-green-100 rounded-lg shadow">
          <img src="https://c.tenor.com/8qOc7rC7qtcAAAAM/animated-greeting-card-earth-day.gif/300x200/?eco,animal" alt="Beneficio 3" class="w-full h-40 object-cover rounded mb-4">
          <h3 class="text-xl font-bold mb-2">Amigable con la fauna</h3>
          <p>No se prueba en animales y utiliza empaques reciclables o biodegradables.</p>
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
          <h3 class="text-xl font-bold mb-2">Duración mejorable</h3>
          <p>Puede requerir varias aplicaciones al día, especialmente en climas cálidos o actividades físicas intensas.</p>
        </li>
        <li class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Período de adaptación</h3>
          <p>Algunos usuarios experimentan sudoración adicional las primeras semanas mientras el cuerpo se regula.</p>
        </li>
        <li class="bg-white p-6 rounded-lg shadow">
          <h3 class="text-xl font-bold mb-2">Precio más elevado</h3>
          <p>Los ingredientes orgánicos y sostenibles suelen tener un costo mayor, pero es una inversión en salud y sostenibilidad.</p>
        </li>
      </ul>
    </div>
  </section>

  <!-- Contacto -->
  <section id="contacto" class="max-w-5xl mx-auto p-8 text-center">
    <h2 class="text-3xl font-bold mb-4">Contáctanos</h2>
    <p class="mb-6">¿Tienes ideas o sugerencias para seguir mejorando? ¡Tu opinión es vital!</p>
    <form class="max-w-md mx-auto">
      <input type="text" placeholder="Nombre" class="w-full p-3 mb-4 border border-green-300 rounded" required />
      <input type="email" placeholder="Correo Electrónico" class="w-full p-3 mb-4 border border-green-300 rounded" required />
      <textarea placeholder="Mensaje" class="w-full p-3 mb-4 border border-green-300 rounded" rows="4" required></textarea>
      <button type="submit" class="bg-green-800 text-white px-6 py-3 rounded hover:bg-green-900">Enviar</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-green-800 text-white text-center p-4">
    <p>&copy; 2025 Frescura Vital. Respeto por tu piel, respeto por la naturaleza.</p>
  </footer>
</body>
</html>
