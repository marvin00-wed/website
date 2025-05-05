<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MARVIN TECH HUB</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
    <style>
        #particles-js {
            position: fixed;
            width: 100%;
            height: 100%;
            background: #1a202c;
            z-index: -1;
        }
        .content {
            position: relative;
            z-index: 1;
        }
        .nav-link:hover {
            color: #4ade80;
        }
    </style>
</head>
<body class="bg-gray-900 text-white font-sans">
    <div id="particles-js"></div>
    <div class="content">
        <!-- Navigation -->
        <nav class="bg-gray-800 p-4 sticky top-0 z-10 shadow-lg">
            <div class="container mx-auto flex justify-between items-center">
                <a href="index.html" class="text-2xl font-bold text-green-400">MARVIN TECH HUB</a>
                <ul class="flex space-x-6">
                    <li><a href="index.html" class="nav-link">Home</a></li>
                    <li><a href="about.html" class="nav-link">About Us</a></li>
                    <li><a href="gallery.html" class="nav-link">Gallery</a></li>
                    <li><a href="services.html" class="nav-link">Services</a></li>
                    <li><a href="contact.html" class="nav-link">Contact Us</a></li>
                </ul>
            </div>
        </nav>

        <!-- Home Page Content -->
        <section class="min-h-screen flex items-center justify-center">
            <div class="container mx-auto text-center">
                <h1 class="text-5xl font-bold mb-4">Welcome to MARVIN TECH HUB</h1>
                <p class="text-xl mb-6">Your ultimate destination for cutting-edge tech solutions and hacking innovations.</p>
                <a href="services.html" class="bg-green-500 text-white px-6 py-3 rounded-lg hover:bg-green-600">Explore Services</a>
            </div>
        </section>

        <!-- Footer -->
        <footer class="bg-gray-800 p-6 text-center">
            <p>&copy; 2025 MARVIN TECH HUB. All rights reserved.</p>
            <p>Contact: <a href="tel:0756714068" class="text-green-400">0756714068</a> | <a href="mailto:leziortera@gmail.com" class="text-green-400">leziortera@gmail.com</a></p>
        </footer>
    </div>

    <script>
        particlesJS('particles-js', {
            particles: {
                number: { value: 80, density: { enable: true, value_area: 800 } },
                color: { value: '#4ade80' },
                shape: { type: 'circle' },
                opacity: { value: 0.5, random: false },
                size: { value: 3, random: true },
                line_linked: { enable: true, distance: 150, color: '#4ade80', opacity: 0.4, width: 1 },
                move: { enable: true, speed: 6, direction: 'none', random: false, straight: false, out_mode: 'out', bounce: false }
            },
            interactivity: {
                detect_on: 'canvas',
                events: { onhover: { enable: true, mode: 'repulse' }, onclick: { enable: true, mode: 'push' }, resize: true },
                modes: { repulse: { distance: 100, duration: 0.4 }, push: { particles_nb: 4 } }
            },
            retina_detect: true
        });
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - MARVIN TECH HUB</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/particles.js@2.0.0/particles.min.js"></script>
    <style>
        #particles-js {
            position: fixed;
            width: 100%;
            height: 100%;
            background: #1a202c;
            z-index: -1;
        }
        .content {
            position: relative;
            z-index: 1;
        }
        .nav-link:hover {
            color: #4ade80;
        }
    </style>
</head>
<body class="bg-gray-900 text-white font-sans">
    <div id="particles-js"></div>
    <div class="content">
        <!-- Navigation -->
        <nav class="bg-gray-800 p-4 sticky top-0 z-10 shadow-lg">
            <div class="container mx-auto flex justify-between items-center">
                <a href="index.html" class="text-2xl font-bold text-green-400">MARVIN TECH HUB</a>
                <ul class="flex space-x-6">
                    <li><a href="index.html" class="nav-link">Home</a></li>
                    <li><a href="about.html" class="nav-link">About Us</a></li>
                    <li><a href="gallery.html" class="nav-link">Gallery</a></li>
                    <li><a href="services.html" class="nav-link">Services</a></li>
                    <li><a href="contact.html" class="nav-link">Contact Us</a></li>
                </ul>
            </div>
        </nav>

        <!-- About Us Content -->
        <section class="min-h-screen flex items-center">
            <div class="container mx-auto px-4">
                <h1 class="text-4xl font-bold mb-6 text-center">About Us</h1>
                <p class="text-lg mb-4">MARVIN TECH HUB is a leading platform for tech enthusiasts and innovators. We specialize in providing cutting-edge solutions in cybersecurity, software development, and ethical hacking.</p>
                <p class="text-lg mb-4">Our mission is to empower individuals and organizations with the knowledge and tools to navigate the digital world securely and efficiently.</p>
                <p class="text-lg">Founded in 2025, we are a team of passionate tech experts dedicated to pushing the boundaries of technology.</p>
            </div>
        </section>

        <!-- Footer -->
        <footer class="bg-gray-800 p-6 text-center">
            <p>&copy; 2025 MARVIN TECH HUB. All rights reserved.</p>
            <p>Contact: <a href="tel:0756714068" class="text-green-400">0756714068</a> | <a href="mailto:leziortera@gmail.com" class="text-green-400">leziortera@gmail.com</a></p>
        </footer>
    </div>

    <script>
        particlesJS('particles-js', {
            particles: {
                number: { value: 80, density: { enable: true, value_area: 800 } },
                color: { value: '#4ade80' },
                shape: { type: 'circle' },
                opacity: { value: 0.5, random: false },
                size: { value: 3, random: true },
                line_linked: { enable: true, distance: 150, color: '#4ade80', opacity: 0.4, width: 1 },
                move: { enable: true, speed: 6, direction: 'none', random: false, straight: false, out_mode: 'out', bounce: false }
            },
            interactivity: {
                detect_on: 'canvas',
                events: { onhover: { enable: true, mode: 'repulse' }, onclick: { enable: true, mode: 'push' }, resize: true },
                modes: { repulse: { distance: 100, duration: 0.4 }, push: { particles_nb: 4 } }
            },
            retina_detect: true
        });
    </script>
</body>
</html>
