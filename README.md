<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Your Name | Portfolio</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-900 font-sans">

  <!-- Header -->
  <header class="bg-white shadow-md">
    <div class="container mx-auto px-4 py-6 flex justify-between items-center">
      <h1 class="text-2xl font-bold">YourName</h1>
      <nav class="space-x-4">
        <a href="#about" class="hover:text-blue-600">About</a>
        <a href="#projects" class="hover:text-blue-600">Projects</a>
        <a href="#contact" class="hover:text-blue-600">Contact</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="text-center py-20 bg-gradient-to-r from-blue-500 to-purple-500 text-white">
    <h2 class="text-4xl font-bold mb-4">Hi, I'm Your Name</h2>
    <p class="text-xl">Graphic Designer & Web Developer</p>
  </section>

  <!-- About -->
  <section id="about" class="py-16 px-4 max-w-3xl mx-auto">
    <h3 class="text-2xl font-bold mb-4">About Me</h3>
    <p>
      I'm a passionate designer and developer specializing in clean, functional websites, engaging motion graphics, and branding. With experience in web development, video editing, and logo animation, I create impactful digital experiences.
    </p>
  </section>

  <!-- Projects -->
  <section id="projects" class="py-16 px-4 bg-white">
    <div class="max-w-5xl mx-auto">
      <h3 class="text-2xl font-bold mb-8 text-center">Projects</h3>
      <div class="grid md:grid-cols-3 gap-6">
        <div class="bg-gray-50 p-4 rounded-lg shadow">
          <img src="project1.jpg" alt="Project 1" class="rounded mb-4" />
          <h4 class="font-bold text-lg">Project Title</h4>
          <p class="text-sm">Short project description.</p>
        </div>
        <div class="bg-gray-50 p-4 rounded-lg shadow">
          <img src="project2.jpg" alt="Project 2" class="rounded mb-4" />
          <h4 class="font-bold text-lg">Project Title</h4>
          <p class="text-sm">Short project description.</p>
        </div>
        <div class="bg-gray-50 p-4 rounded-lg shadow">
          <img src="project3.jpg" alt="Project 3" class="rounded mb-4" />
          <h4 class="font-bold text-lg">Project Title</h4>
          <p class="text-sm">Short project description.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Contact -->
  <section id="contact" class="py-16 px-4 max-w-3xl mx-auto">
    <h3 class="text-2xl font-bold mb-4">Contact Me</h3>
    <form action="https://formspree.io/f/yourformid" method="POST" class="space-y-4">
      <input type="text" name="name" placeholder="Your Name" required class="w-full p-2 border rounded" />
      <input type="email" name="email" placeholder="Your Email" required class="w-full p-2 border rounded" />
      <textarea name="message" rows="5" placeholder="Your Message" required class="w-full p-2 border rounded"></textarea>
      <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded hover:bg-blue-700">Send</button>
    </form>
  </section>

  <!-- Footer -->
  <footer class="bg-white py-6 text-center text-sm">
    © 2025 Your Name. All rights reserved.
  </footer>

</body>
</html>
