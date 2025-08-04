# the-forrest-roblox.github.io
a roblox horror in beta
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>www.theforrest.com</title>
    <!-- Tailwind CSS CDN for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Font "Inter" for a clean, modern look -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap');
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-950 text-white leading-relaxed">
    
    <!-- Header/Navbar -->
    <header class="fixed top-0 left-0 w-full z-50 bg-black/80 backdrop-blur-sm shadow-lg">
        <nav class="container mx-auto p-4 flex justify-between items-center">
            <!-- Game Logo -->
            <a href="#" class="flex items-center space-x-2">
                <!-- Using a placeholder for the logo -->
                <img src="https://placehold.co/40x40/000000/ffffff?text=Logo" alt="The Forrest Logo" class="h-10 rounded-lg">
            </a>
            <a href="https://www.roblox.com/games/116231981979660/forest-beta" target="_blank" rel="noopener noreferrer" class="bg-red-600 hover:bg-red-700 text-white font-semibold py-2 px-6 rounded-full transition-colors duration-300 shadow-md">
                Play Now
            </a>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="relative h-screen flex items-center justify-center text-center">
        <!-- Using a placeholder for the hero background -->
        <div class="absolute inset-0 bg-cover bg-center" style="background-image: url('https://placehold.co/1920x1080/1a202c/e2e8f0?text=The+Forrest');">
            <div class="absolute inset-0 bg-black opacity-70"></div>
        </div>
        <div class="relative z-10 px-4 md:px-8">
            <h1 class="text-4xl md:text-6xl font-bold mb-4 animate-fade-in-up">Welcome to The Forrest</h1>
            <p class="text-lg md:text-2xl text-gray-300 max-w-2xl mx-auto mb-8 animate-fade-in-up delay-100">
                A horror game where you have to survive in the forrest. Every shadow hides a secret and every rustle could be your last.
            </p>
            <a href="https://www.roblox.com/games/116231981979660/forest-beta" target="_blank" rel="noopener noreferrer" class="bg-red-500 hover:bg-red-600 text-white font-bold py-3 px-8 rounded-full text-lg transition-all duration-300 transform hover:scale-105 shadow-xl animate-fade-in-up delay-200">
                Start Your Journey
            </a>
        </div>
    </section>

    <!-- About/Story Section -->
    <section id="about" class="py-20 md:py-32 container mx-auto px-4 md:px-8">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div class="space-y-6">
                <h2 class="text-4xl font-bold text-red-400">The Story Begins...</h2>
                <p class="text-gray-300">
                    You awaken to the eerie silence of a dense, unforgiving forest. The last thing you remember is a blinding light and a chilling sound. Now, all that's left is the whispering wind and the feeling of being watched. You must brave the elements, find resources, and uncover the dark secrets of this forgotten land.
                </p>
                <p class="text-gray-400 italic">
                    "The forest is alive. And it's hungry."
                </p>
            </div>
            <!-- Using a placeholder for the about section image -->
            <div class="p-2 bg-gray-800 rounded-xl shadow-2xl transform hover:scale-105 transition-transform duration-300">
                <img src="https://placehold.co/800x600/2d3748/a0aec0?text=Game+Screenshot" alt="A screenshot from the game The Forrest" class="rounded-lg w-full">
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 md:py-32 bg-gray-900">
        <div class="container mx-auto px-4 md:px-8 text-center">
            <h2 class="text-4xl font-bold mb-12 text-red-400">Key Features</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Feature Card 1 -->
                <div class="bg-gray-950 p-8 rounded-xl shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <svg class="h-16 w-16 text-red-500 mx-auto mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20 7l-8-4-8 4m16 0l-8 4m8-4v10l-8 4m0-10L4 7m8 4v10m0-10l-8 4m8-4v10"/>
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Resource Management</h3>
                    <p class="text-gray-400">
                        Gather wood, hunt for food, and craft tools to survive the harsh environment.
                    </p>
                </div>
                <!-- Feature Card 2 -->
                <div class="bg-gray-950 p-8 rounded-xl shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <svg class="h-16 w-16 text-red-500 mx-auto mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6.253v13m0-13C10.835 5.568 9.5 5 8 5c-3.18 0-4.57 2.37-4.57 4.5 0 2.87 3.57 5.5 4.57 5.5s4.57-2.63 4.57-5.5c0-2.13-1.39-4.5-4.57-4.5zm1.5-1.5v13m0-13C13.165 5.568 14.5 5 16 5c3.18 0 4.57 2.37 4.57 4.5 0 2.87-3.57 5.5-4.57 5.5s-4.57-2.63-4.57-5.5c0-2.13 1.39-4.5 4.57-4.5z"/>
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Uncover the Mystery</h3>
                    <p class="text-gray-400">
                        Explore hidden caves and abandoned camps to piece together the truth of what happened.
                    </p>
                </div>
                <!-- Feature Card 3 -->
                <div class="bg-gray-950 p-8 rounded-xl shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <svg class="h-16 w-16 text-red-500 mx-auto mb-4" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z" />
                    </svg>
                    <h3 class="text-xl font-semibold mb-2">Play with Friends</h3>
                    <p class="text-gray-400">
                        Work together with other players to increase your chances of survival in the dangerous wilderness.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section id="play-now" class="py-20 md:py-32 text-center bg-gray-950">
        <div class="container mx-auto px-4 md:px-8">
            <h2 class="text-4xl font-bold mb-4 text-red-400">Are You Ready to Survive?</h2>
            <p class="text-lg text-gray-300 max-w-3xl mx-auto mb-8">
                Join thousands of other players in The Forrest today. The adventure awaits.
            </p>
            <!-- Replace this with your actual Roblox game link -->
            <a href="https://www.roblox.com/games/116231981979660/forest-beta" target="_blank" rel="noopener noreferrer"
               class="inline-block bg-red-600 hover:bg-red-700 text-white font-bold py-4 px-10 rounded-full text-xl transition-all duration-300 transform hover:scale-110 shadow-lg">
                Play The Forrest on Roblox
            </a>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-950 text-gray-500 py-8">
        <div class="container mx-auto px-4 md:px-8 text-center">
            <p>&copy; 2025 The Forrest. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>

