<!DOCTYPE html>
<html lang="en">

<head>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ayush Patel- Portfolio</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>

<body class="bg-gray-100 text-gray-800">
    <!-- Navigation -->
    <nav class="bg-white shadow">
        <div class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="text-lg font-semibold"> Ayush Patel</div>
                <div class="space-x-4">
                    <a href="#about" class="hover:text-gray-600">About</a>
                    <a href="#projects" class="hover:text-gray-600">Projects</a>
                    <a href="#contact" class="hover:text-gray-600">Contact</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="bg-blue-600 text-white py-20">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl font-bold mb-4">Hello, there!</h1>
            <p class="text-xl">I'm a passionate developer who loves building amazing things.</p>
        </div>
    </header>

    <!-- About Section -->
    <section id="about" class="py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-8">About Me</h2>
            <p class="text-center max-w-2xl mx-auto">
                I'm a software developer with experience in building web applications, mobile apps, and more. I love
                solving problems and creating user-friendly experiences.
            </p>
        </div>
    </section>

    <!-- Projects Section -->
    <section id="projects" class="bg-white py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-8">Projects</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Project 1 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">Tinder Clone</h3>
                    <p>I've created a clone website of tinder to practice and enhance my coding skills.</p>
                </div>
                <!-- Project 2 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">Notestack</h3>
                    <p>Using basics of React.JS I've made a note displaying website.</p>
                </div>
                <!-- Project 3 -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-lg">
                    <h3 class="text-xl font-bold mb-2">CRUD Application</h3>
                    <p>Created a CRUD application where you can create, read, update, and delete contents.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-8">Contact Me</h2>
            <form class="max-w-lg mx-auto">
                <div class="mb-4">
                    <label for="name" class="block text-sm font-medium mb-2">Name</label>
                    <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg" placeholder="Your Name">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-sm font-medium mb-2">Email</label>
                    <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg" placeholder="Your Email">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-sm font-medium mb-2">Message</label>
                    <textarea id="message" class="w-full px-4 py-2 border rounded-lg" rows="4"
                        placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">Send
                    Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <p>&copy; 2025 Ayush Patel . All rights reserved.</p>
        </div>
    </footer>
</body>

</html>
