<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bigwilliecigars.store | Premium Handcrafted Cigars</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for custom colors and font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'primary-dark': '#1c1917', // Stone-900 for background
                        'accent-gold': '#a67c55', // Brass/Gold accent
                        'mahogany': '#4b1f0c',    // Deep Brown/Mahogany
                    },
                    fontFamily: {
                        // Using Inter as the default, but will use a serif style for titles
                        sans: ['Inter', 'sans-serif'],
                        serif: ['Georgia', 'serif'],
                    }
                }
            }
        }
    </script>
    <style>
        /* Custom styles for luxurious shadow and glow effect */
        .card-shadow {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.5), 0 2px 4px -2px rgba(0, 0, 0, 0.5), 0 0 10px rgba(166, 124, 85, 0.3);
        }
    </style>
</head>
<body class="bg-primary-dark text-gray-200 font-sans antialiased">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-primary-dark bg-opacity-95 shadow-xl border-b border-mahogany/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-20">
                <!-- Logo -->
                <a href="#" class="text-3xl font-serif font-bold tracking-widest text-accent-gold uppercase">
                    Bigwillie<span class="text-gray-200">Cigars</span>
                </a>

                <!-- Desktop Navigation -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#featured" class="text-lg text-gray-200 hover:text-accent-gold transition duration-300">Featured</a>
                    <a href="#collections" class="text-lg text-gray-200 hover:text-accent-gold transition duration-300">Collections</a>
                    <a href="#about" class="text-lg text-gray-200 hover:text-accent-gold transition duration-300">Our Story</a>
                    <a href="#contact" class="text-lg text-gray-200 hover:text-accent-gold transition duration-300">Contact</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="mobile-menu-button" class="md:hidden p-2 text-gray-200 hover:text-accent-gold transition duration-300 focus:outline-none" aria-label="Toggle Menu">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu Drawer (Hidden by Default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-mahogany/95 backdrop-blur-sm">
            <nav class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#featured" class="block px-3 py-2 rounded-md text-base font-medium text-gray-100 hover:bg-primary-dark/50 transition duration-300">Featured</a>
                <a href="#collections" class="block px-3 py-2 rounded-md text-base font-medium text-gray-100 hover:bg-primary-dark/50 transition duration-300">Collections</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-100 hover:bg-primary-dark/50 transition duration-300">Our Story</a>
                <a href="#contact" class="block px-3 py-2 rounded-md text-base font-medium text-gray-100 hover:bg-primary-dark/50 transition duration-300">Contact</a>
            </nav>
        </div>
    </header>

    <main>
        <!-- Hero Section -->
        <section id="hero" class="relative overflow-hidden">
            <div class="absolute inset-0 bg-cover bg-center opacity-30" style="background-image: url('https://placehold.co/1920x800/4b1f0c/ffffff?text=Aged+Tobacco+Leaves');"></div>
            <div class="relative max-w-7xl mx-auto py-20 md:py-36 px-4 sm:px-6 lg:px-8 text-center">
                <h1 class="text-5xl md:text-7xl font-serif font-extrabold tracking-tight text-white mb-4 card-shadow p-2">
                    The Art of The Smoke
                </h1>
                <p class="text-xl md:text-2xl text-gray-300 mb-8 max-w-3xl mx-auto">
                    Hand-rolled perfection, aged to distinction. Discover the heritage and robust flavor that defines true premium tobacco.
                </p>
                <a href="#featured" class="inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-full text-primary-dark bg-accent-gold hover:bg-amber-400 transition duration-300 shadow-lg hover:shadow-xl transform hover:scale-105">
                    Explore Our Heritage Blends
                </a>
            </div>
        </section>

        <!-- Featured Products Section -->
        <section id="featured" class="py-16 md:py-24 bg-primary-dark">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h2 class="text-4xl font-serif font-bold text-center text-accent-gold mb-12">Featured Selections</h2>

                <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">

                    <!-- Product Card 1 -->
                    <div class="bg-mahogany rounded-xl overflow-hidden card-shadow p-6 transition duration-500 hover:scale-[1.02] hover:bg-mahogany/80">
                        <div class="w-full h-48 bg-gray-700 rounded-lg mb-4 flex items-center justify-center">
                            <img src="https://placehold.co/400x300/444/999?text=The+Chairman+Cigar" alt="The Chairman Cigar" class="w-full h-full object-cover rounded-lg" onerror="this.onerror=null;this.src='https://placehold.co/400x300/444/999?text=The+Chairman+Cigar';" />
                        </div>
                        <h3 class="text-2xl font-serif font-semibold text-gray-50 mb-2">The Chairman Reserve</h3>
                        <p class="text-gray-300 text-sm mb-4">A rich, full-bodied smoke with notes of leather, coffee, and dark chocolate. Perfect for evening relaxation.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-2xl font-bold text-accent-gold">$18.99</span>
                            <button class="px-4 py-2 bg-accent-gold text-primary-dark text-sm font-semibold rounded-full hover:bg-amber-400 transition duration-300">Add to Cart</button>
                        </div>
                    </div>

                    <!-- Product Card 2 -->
                    <div class="bg-mahogany rounded-xl overflow-hidden card-shadow p-6 transition duration-500 hover:scale-[1.02] hover:bg-mahogany/80">
                        <div class="w-full h-48 bg-gray-700 rounded-lg mb-4 flex items-center justify-center">
                            <img src="https://placehold.co/400x300/444/999?text=Platinum+Sampler+Box" alt="Platinum Sampler Box" class="w-full h-full object-cover rounded-lg" onerror="this.onerror=null;this.src='https://placehold.co/400x300/444/999?text=Platinum+Sampler+Box';" />
                        </div>
                        <h3 class="text-2xl font-serif font-semibold text-gray-50 mb-2">Platinum Sampler Box</h3>
                        <p class="text-gray-300 text-sm mb-4">Experience a range of our best sellers. Five unique blends, perfect for the discerning beginner or seasoned connoisseur.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-2xl font-bold text-accent-gold">$79.50</span>
                            <button class="px-4 py-2 bg-accent-gold text-primary-dark text-sm font-semibold rounded-full hover:bg-amber-400 transition duration-300">Add to Cart</button>
                        </div>
                    </div>

                    <!-- Product Card 3 -->
                    <div class="bg-mahogany rounded-xl overflow-hidden card-shadow p-6 transition duration-500 hover:scale-[1.02] hover:bg-mahogany/80">
                        <div class="w-full h-48 bg-gray-700 rounded-lg mb-4 flex items-center justify-center">
                            <img src="https://placehold.co/400x300/444/999?text=Connecticut+Wrapper" alt="Connecticut Wrapper Cigar" class="w-full h-full object-cover rounded-lg" onerror="this.onerror=null;this.src='https://placehold.co/400x300/444/999?text=Connecticut+Wrapper';" />
                        </div>
                        <h3 class="text-2xl font-serif font-semibold text-gray-50 mb-2">The Smooth Connecticut</h3>
                        <p class="text-gray-300 text-sm mb-4">A lighter, creamy smoke with a delicate wrapper and hints of cedar and spice. Ideal for a morning or afternoon enjoyment.</p>
                        <div class="flex items-center justify-between">
                            <span class="text-2xl font-bold text-accent-gold">$12.99</span>
                            <button class="px-4 py-2 bg-accent-gold text-primary-dark text-sm font-semibold rounded-full hover:bg-amber-400 transition duration-300">Add to Cart</button>
                        </div>
                    </div>

                </div>
            </div>
        </section>

        <!-- Our Story / About Section -->
        <section id="about" class="py-16 md:py-24 bg-primary-dark border-t border-b border-mahogany">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="lg:grid lg:grid-cols-2 lg:gap-12 items-center">
                    <div class="mb-10 lg:mb-0">
                        <h2 class="text-4xl font-serif font-bold text-accent-gold mb-6">Our Legacy of Smoke</h2>
                        <p class="text-lg text-gray-300 mb-4">
                            Bigwilliecigars.store was founded on a simple principle: to honor the age-old tradition of fine tobacco. Every single cigar in our selection is sourced from boutique, family-owned farms in the richest valleys of Nicaragua, the Dominican Republic, and Honduras.
                        </p>
                        <p class="text-lg text-gray-300 mb-6">
                            We don't just sell cigars; we curate experiences. From the carefully aged binder to the perfectly fermented wrapper, we guarantee a flawless draw and an unforgettable flavor profile in every box. Welcome to the family.
                        </p>
                        <a href="#contact" class="inline-flex items-center text-lg font-semibold text-accent-gold hover:text-amber-400 transition duration-300">
                            Meet Our Master Blender &rarr;
                        </a>
                    </div>
                    <div class="h-64 md:h-96 w-full rounded-xl overflow-hidden card-shadow">
                        <img src="https://placehold.co/800x600/4b1f0c/ffffff?text=Tobacco+Field" alt="Tobacco fields in the sunset" class="w-full h-full object-cover" onerror="this.onerror=null;this.src='https://placehold.co/800x600/4b1f0c/ffffff?text=Tobacco+Field';" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Newsletter CTA Section -->
        <section class="py-16 bg-mahogany">
            <div class="max-w-xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h3 class="text-3xl font-serif font-bold text-accent-gold mb-4">Join The Private Reserve</h3>
                <p class="text-gray-300 mb-6">Sign up for exclusive releases, early access to limited editions, and 10% off your first order.</p>
                <form class="flex flex-col sm:flex-row gap-4 justify-center">
                    <input type="email" placeholder="Enter your email address" class="w-full sm:w-80 px-4 py-3 rounded-lg bg-primary-dark text-gray-50 border border-mahogany/50 focus:border-accent-gold focus:outline-none" required>
                    <button type="submit" class="px-6 py-3 bg-accent-gold text-primary-dark font-semibold rounded-lg hover:bg-amber-400 transition duration-300 shadow-md">Subscribe</button>
                </form>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer id="contact" class="bg-primary-dark border-t border-mahogany/50 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <!-- Col 1: Logo & Info -->
                <div>
                    <h4 class="text-xl font-serif font-bold tracking-widest text-accent-gold mb-4">Bigwilliecigars</h4>
                    <p class="text-sm text-gray-400 mb-2">Aged to Perfection.</p>
                    <p class="text-sm text-gray-400">© 2024. All Rights Reserved.</p>
                </div>

                <!-- Col 2: Navigation -->
                <div>
                    <h4 class="text-lg font-semibold text-gray-50 mb-4">Quick Links</h4>
                    <ul class="space-y-2">
                        <li><a href="#featured" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">Shop Now</a></li>
                        <li><a href="#about" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">Our Story</a></li>
                        <li><a href="#" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">Wholesale</a></li>
                    </ul>
                </div>

                <!-- Col 3: Support -->
                <div>
                    <h4 class="text-lg font-semibold text-gray-50 mb-4">Support</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">FAQ</a></li>
                        <li><a href="#" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">Shipping & Returns</a></li>
                        <li><a href="#" class="text-sm text-gray-400 hover:text-accent-gold transition duration-300">Privacy Policy</a></li>
                    </ul>
                </div>

                <!-- Col 4: Contact -->
                <div>
                    <h4 class="text-lg font-semibold text-gray-50 mb-4">Reach Out</h4>
                    <p class="text-sm text-gray-400">Email: <a href="mailto:info@bigwilliecigars.store" class="hover:text-accent-gold">info@bigwilliecigars.store</a></p>
                    <p class="text-sm text-gray-400 mt-2">Phone: (555) 555-CIGAR</p>
                </div>
            </div>
        </div>
    </footer>

    <!-- JavaScript for Mobile Menu and Smooth Scroll -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const menuButton = document.getElementById('mobile-menu-button');
            const mobileMenu = document.getElementById('mobile-menu');

            // 1. Mobile Menu Toggle
            menuButton.addEventListener('click', () => {
                const isExpanded = menuButton.getAttribute('aria-expanded') === 'true' || false;
                menuButton.setAttribute('aria-expanded', !isExpanded);
                mobileMenu.classList.toggle('hidden');
            });

            // 2. Smooth Scrolling and closing menu on mobile click
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);

                    if (targetElement) {
                        // Close mobile menu if open
                        if (!mobileMenu.classList.contains('hidden')) {
                            mobileMenu.classList.add('hidden');
                            menuButton.setAttribute('aria-expanded', 'false');
                        }

                        // Smooth scroll to target
                        window.scrollTo({
                            top: targetElement.offsetTop - 80, // Offset for fixed header
                            behavior: 'smooth'
                        });
                    }
                });
            });
        });
    </script>
</body>
</html>
