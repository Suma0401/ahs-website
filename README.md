<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Advance Healthcare Solutions</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 text-gray-900 font-sans">
  <header class="bg-blue-800 text-white p-6 shadow">
    <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between">
      <div>
        <h1 class="text-3xl font-bold">Advance Healthcare Solutions</h1>
        <p class="text-lg">Your Trusted Partner in Medical Billing</p>
      </div>
      <a href="#contact" class="mt-4 md:mt-0 bg-white text-blue-800 px-5 py-2 rounded hover:bg-gray-100">Get Started</a>
    </div>
  </header>

  <nav class="bg-white shadow-md">
    <div class="max-w-7xl mx-auto px-4 py-3 flex justify-between">
      <ul class="flex space-x-6 text-blue-800 font-medium">
        <li><a href="#about" class="hover:text-blue-500">About</a></li>
        <li><a href="#services" class="hover:text-blue-500">Services</a></li>
        <li><a href="#benefits" class="hover:text-blue-500">Why Choose Us</a></li>
        <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
      </ul>
    </div>
  </nav>

  <main class="max-w-7xl mx-auto p-6">
    <section id="about" class="my-10">
      <h2 class="text-2xl font-bold mb-4">About Us</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <div>
          <h3 class="text-xl font-semibold">Our Mission</h3>
          <p>Empowering healthcare providers with streamlined, accurate, and compliant medical billing services...</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold">Our Vision</h3>
          <p>To be the leading partner in optimizing healthcare financial management...</p>
        </div>
      </div>
    </section>

    <section id="services" class="my-10">
      <h2 class="text-2xl font-bold mb-4">Our Services</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <ul class="list-disc list-inside space-y-2">
          <li>Patient Registration and Demographics</li>
          <li>Medical Coding</li>
          <li>Charge Entry</li>
          <li>Claim Submission</li>
          <li>Claims Processing and Adjudication</li>
        </ul>
        <ul class="list-disc list-inside space-y-2">
          <li>Payment Posting</li>
          <li>Denial Management and Re-submission</li>
          <li>Patient Billing and Statements</li>
          <li>Follow-Up and Collections</li>
          <li>Appeals and Disputes</li>
        </ul>
      </div>
    </section>

    <section id="benefits" class="my-10">
      <h2 class="text-2xl font-bold mb-4">Why Choose Us</h2>
      <div class="grid md:grid-cols-2 gap-6">
        <ul class="list-disc list-inside space-y-2">
          <li>Maximized Revenue</li>
          <li>Reduced Administrative Burden</li>
          <li>Improved Cash Flow</li>
          <li>Minimized Claim Denials</li>
        </ul>
        <ul class="list-disc list-inside space-y-2">
          <li>Cutting-Edge Technology</li>
          <li>HIPAA Compliance</li>
          <li>Customized Solutions</li>
          <li>Expert Coding</li>
        </ul>
      </div>
    </section>

    <section id="contact" class="my-10">
      <h2 class="text-2xl font-bold mb-4">Contact Us</h2>
      <p>Email: <a href="mailto:info.advancehealthcaresolutions@gmail.com" class="text-blue-600 hover:underline">info.advancehealthcaresolutions@gmail.com</a></p>
            <form class="mt-6 grid grid-cols-1 gap-4 max-w-lg">
        <input type="text" placeholder="Your Name" class="p-2 border rounded" required />
        <input type="email" placeholder="Your Email" class="p-2 border rounded" required />
        <textarea placeholder="Your Message" class="p-2 border rounded h-32" required></textarea>
        <button type="submit" class="bg-blue-800 text-white py-2 px-4 rounded hover:bg-blue-900">Send Message</button>
      </form>
    </section>
  </main>

  <footer class="bg-gray-800 text-white text-center p-4">
    &copy; 2025 Advance Healthcare Solutions. All rights reserved.
  </footer>
</body>
</html>
