<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GitHub Profile</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    .fade-in {
      animation: fadeIn 2s ease-in-out;
    }

    .slide-up {
      animation: slideUp 1s ease-in-out;
    }

    @keyframes fadeIn {
      from { opacity: 0; }
      to { opacity: 1; }
    }

    @keyframes slideUp {
      from { transform: translateY(20px); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }
  </style>
</head>
<body class="bg-gray-900 text-white font-sans">
  <div class="max-w-4xl mx-auto p-8">
    <header class="text-center fade-in">
      <h1 class="text-4xl font-bold mb-2">Hola, soy Giovanni Medina Molina 👋</h1>
      <p class="text-lg text-gray-300">Desarrollador Web especializado en React, TypeScript y tecnologías modernas</p>
    </header>

    <section class="mt-10 slide-up">
      <h2 class="text-2xl font-semibold mb-4 text-blue-400">🚀 Tecnologías que uso</h2>
      <div class="grid grid-cols-2 md:grid-cols-3 gap-4 text-center">
        <div class="bg-gray-800 p-4 rounded-lg">React</div>
        <div class="bg-gray-800 p-4 rounded-lg">TypeScript</div>
        <div class="bg-gray-800 p-4 rounded-lg">JavaScript</div>
        <div class="bg-gray-800 p-4 rounded-lg">HTML5</div>
        <div class="bg-gray-800 p-4 rounded-lg">Tailwind CSS</div>
        <div class="bg-gray-800 p-4 rounded-lg">CSS3</div>
        <div class="bg-gray-800 p-4 rounded-lg">Express.js</div>
        <div class="bg-gray-800 p-4 rounded-lg">TablePlus</div>
      </div>
    </section>

    <section class="mt-10 slide-up">
      <h2 class="text-2xl font-semibold mb-4 text-green-400">📈 Actualmente trabajando en:</h2>
      <p class="text-gray-300">Desarrollo de aplicaciones fullstack con React + Express.js, usando bases de datos relacionales y estilizando con TailwindCSS.</p>
    </section>

    <section class="mt-10 slide-up">
      <h2 class="text-2xl font-semibold mb-4 text-yellow-400">📫 Cómo contactarme</h2>
      <p class="text-gray-300">Puedes escribirme por correo: <a href="mailto:giovanni@email.com" class="text-blue-400 hover:underline">giovanni@email.com</a></p>
      <p class="text-gray-300">O conectar conmigo en <a href="https://github.com/tu_usuario" class="text-blue-400 hover:underline">GitHub</a></p>
    </section>
  </div>
</body>
</html>
