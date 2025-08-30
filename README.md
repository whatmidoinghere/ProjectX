
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cronette - Handcrafted Crochet Dresses</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap');
        <img src="https://your-image![IMG-20250824-WA0233](https://github.com/user-attachments/assets/9c87c1b8-fa22-4e7a-8075-761ea4d1d96b)

        
        .font-playfair { font-family: 'Playfair Display', serif; }
        .font-inter { font-family: 'Inter', sans-serif; }
        
        .hero-pattern {
            background-image: 
                radial-gradient(circle at 25% 25%, rgba(255, 182, 193, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 75% 75%, rgba(255, 218, 185, 0.1) 0%, transparent 50%);
        }
        
        .crochet-pattern {
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 10px, rgba(255, 182, 193, 0.05) 10px, rgba(255, 182, 193, 0.05) 20px);
        }
        
        .floating {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .fade-in {
            animation: fadeIn 0.8s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .nav-link {
            position: relative;
            transition: all 0.3s ease;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 50%;
            background: linear-gradient(90deg, #f472b6, #fb7185);
            transition: all 0.3s ease;
            transform: translateX(-50%);
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="font-inter bg-gradient-to-br from-pink-50 via-white to-orange-50 min-h-screen">
    <!-- Navigation -->
    <nav class="bg-white/80 backdrop-blur-md shadow-sm sticky top-0 z-50 border-b border-pink-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <h1 class="font-playfair text-3xl font-bold bg-gradient-to-r from-pink-500 to-rose-500 bg-clip-text text-transparent">
                    Cronette
                </h1>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Home</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-pink-500 font-medium">About</a>
                    <a href="#products" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Products</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Contact</a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden p-2 rounded-md text-gray-700 hover:text-pink-500">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-pink-100">
            <div class="px-4 py-2 space-y-2">
                <a href="#home" class="block py-2 text-gray-700 hover:text-pink-500">Home</a>
                <a href="#about" class="block py-2 text-gray-700 hover:text-pink-500">About</a>
                <a href="#products" class="block py-2 text-gray-700 hover:text-pink-500">Products</a>
                <a href="#contact" class="block py-2 text-gray-700 hover:text-pink-500">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-pattern py-20 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <div class="floating">
                <div class="text-6xl mb-6">🧶</div>
            </div>
            <h2 class="font-playfair text-5xl md:text-6xl font-bold text-gray-800 mb-6 fade-in">
                Handcrafted with
                <span class="bg-gradient-to-r from-pink-500 to-rose-500 bg-clip-text text-transparent">Love</span>
            </h2>
            <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto leading-relaxed fade-in">
                Cronette creates unique and beautiful dresses - each a unique piece of art that showcases the skills and creativity of the maker.
            </p>
            <button class="bg-gradient-to-r from-pink-500 to-rose-500 text-white px-8 py-4 rounded-full font-semibold text-lg hover:from-pink-600 hover:to-rose-600 transform hover:scale-105 transition-all duration-300 shadow-lg hover:shadow-xl">
                Explore Collection
            </button>
        </div>
    </section>

    <!-- Features Section -->
    <section id="about" class="py-20 px-4 bg-white">
        <div class="max-w-6xl mx-auto">
            <h3 class="font-playfair text-4xl font-bold text-center text-gray-800 mb-16">
                Why Choose Cronette?
            </h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="card-hover bg-gradient-to-br from-pink-50 to-rose-50 p-8 rounded-2xl border border-pink-100">
                    <div class="text-4xl mb-4">✨</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">One of a Kind</h4>
                    <p class="text-gray-600 leading-relaxed">Each dress is carefully crafted by hand, making it a truly one-of-kind piece that you won't find anywhere else.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-orange-50 to-pink-50 p-8 rounded-2xl border border-orange-100">
                    <div class="text-4xl mb-4">💝</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Attention to Detail</h4>
                    <p class="text-gray-600 leading-relaxed">The maker puts love and care into every stitch, ensuring a high level of quality and attention to detail.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-purple-50 to-pink-50 p-8 rounded-2xl border border-purple-100">
                    <div class="text-4xl mb-4">📏</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Customizable</h4>
                    <p class="text-gray-600 leading-relaxed">Hand-made crochet dresses can be tailored to fit the wearer's specific measurements and style preferences.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-green-50 to-emerald-50 p-8 rounded-2xl border border-green-100">
                    <div class="text-4xl mb-4">🌱</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Sustainable</h4>
                    <p class="text-gray-600 leading-relaxed">Crochet dresses made from eco-friendly yarns are a sustainable alternative to fast fashion.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 px-4 crochet-pattern">
        <div class="max-w-6xl mx-auto">
            <h3 class="font-playfair text-4xl font-bold text-center text-gray-800 mb-16">
                Featured Collection
            </h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-pink-200 to-rose-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Summer Breeze Dress</h4>
                        <p class="text-gray-600 mb-4">Light and airy crochet dress perfect for warm days</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵450</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-purple-200 to-pink-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Elegant Evening Dress</h4>
                        <p class="text-gray-600 mb-4">Sophisticated design for special occasions</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵650</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-orange-200 to-pink-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Bohemian Maxi Dress</h4>
                        <p class="text-gray-600 mb-4">Free-spirited design with intricate patterns</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵550</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4 bg-gradient-to-br from-pink-500 to-rose-500 text-white">
        <div class="max-w-4xl mx-auto text-center">
            <h3 class="font-playfair text-4xl font-bold mb-8">Get in Touch</h3>
            <p class="text-xl mb-12 opacity-90">Ready to create your perfect dress? Let's bring your vision to life!</p>
            
            <div class="grid md:grid-cols-3 gap-8 mb-12">
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📧</div>
                    <h4 class="font-semibold mb-2">Email Us</h4>
                    <p class="opacity-90">hello@cronette.com</p>
                </div>
                
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📱</div>
                    <h4 class="font-semibold mb-2">Call Us</h4>
                    <p class="opacity-90">+233 53 597 7147</p>
                </div>
                
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📍</div>
                    <h4 class="font-semibold mb-2">Visit Us</h4>
                    <p class="opacity-90">Tema, Ghana</p>
                </div>
            </div>
            
            <button class="bg-white text-pink-500 px-8 py-4 rounded-full font-semibold text-lg hover:bg-gray-50 transform hover:scale-105 transition-all duration-300 shadow-lg">
                Start Your Custom Order
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <h1 class="font-playfair text-3xl font-bold mb-4 bg-gradient-to-r from-pink-400 to-rose-400 bg-clip-text text-transparent">
                Cronette
            </h1>
            <p class="text-gray-400 mb-6">Handcrafted crochet dresses made with love</p>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                    </svg>
                </a>
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12.017 0C5.396 0 .029 5.367.029 11.987c0 5.079 3.158 9.417 7.618 11.174-.105-.949-.199-2.403.041-3.439.219-.937 1.406-5.957 1.406-5.957s-.359-.72-.359-1.781c0-1.663.967-2.911 2.168-2.911 1.024 0 1.518.769 1.518 1.688 0 1.029-.653 2.567-.992 3.992-.285 1.193.6 2.165 1.775 2.165 2.128 0 3.768-2.245 3.768-5.487 0-2.861-2.063-4.869-5.008-4.869-3.41 0-5.409 2.562-5.409 5.199 0 1.033.394 2.143.889 2.741.097.118.112.221.085.345-.09.375-.293 1.199-.334 1.363-.053.225-.172.271-.402.165-1.495-.69-2.433-2.878-2.433-4.646 0-3.776 2.748-7.252 7.92-7.252 4.158 0 7.392 2.967 7.392 6.923 0 4.135-2.607 7.462-6.233 7.462-1.214 0-2.357-.629-2.748-1.378l-.748 2.853c-.271 1.043-1.002 2.35-1.492 3.146C9.57 23.812 10.763 24.009 12.017 24.009c6.624 0 11.99-5.367 11.99-11.988C24.007 5.367 18.641.001.012.001z.017 0z"/>
                    </svg>
                </a>
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                    </svg>
                </a>
            </div>
            <p class="text-gray-500 text-sm">© 2024 Cronette. All rights reserved. Made with 💖 and lots of yarn.</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Close mobile menu if open
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('bg-white/90');
            } else {
                nav.classList.remove('bg-white/90');
            }
        });

        // Add click functionality to buttons
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.includes('Explore Collection')) {
                button.addEventListener('click', () => {
                    document.getElementById('products').scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            } else if (button.textContent.includes('View Details')) {
                button.addEventListener('click', () => {
                    alert('Product details coming soon! Contact us for more information.');
                });
            } else if (button.textContent.includes('Start Your Custom Order')) {
                button.addEventListener('click', () => {
                    alert('Thank you for your interest! We\'ll be in touch soon to discuss your custom order.');
                });
            }
        });

        // Add fade-in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, observerOptions);

        // Observe all cards and sections
        document.querySelectorAll('.card-hover, section').forEach(el => {
            observer.observe(el);
        });
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'975fc85430f67f07',t:'MTc1NjM0MTg5MS4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cronette - Handcrafted Crochet Dresses</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;600;700&family=Inter:wght@300;400;500;600&display=swap');
        
        .font-playfair { font-family: 'Playfair Display', serif; }
        .font-inter { font-family: 'Inter', sans-serif; }
        
        .hero-pattern {
            background-image: 
                radial-gradient(circle at 25% 25%, rgba(255, 182, 193, 0.1) 0%, transparent 50%),
                radial-gradient(circle at 75% 75%, rgba(255, 218, 185, 0.1) 0%, transparent 50%);
        }
        
        .crochet-pattern {
            background-image: 
                repeating-linear-gradient(45deg, transparent, transparent 10px, rgba(255, 182, 193, 0.05) 10px, rgba(255, 182, 193, 0.05) 20px);
        }
        
        .floating {
            animation: float 6s ease-in-out infinite;
        }
        
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
        }
        
        .fade-in {
            animation: fadeIn 0.8s ease-in-out;
        }
        
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        
        .nav-link {
            position: relative;
            transition: all 0.3s ease;
        }
        
        .nav-link::after {
            content: '';
            position: absolute;
            width: 0;
            height: 2px;
            bottom: -5px;
            left: 50%;
            background: linear-gradient(90deg, #f472b6, #fb7185);
            transition: all 0.3s ease;
            transform: translateX(-50%);
        }
        
        .nav-link:hover::after {
            width: 100%;
        }
        
        .card-hover {
            transition: all 0.3s ease;
        }
        
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body class="font-inter bg-gradient-to-br from-pink-50 via-white to-orange-50 min-h-screen">
    <!-- Navigation -->
    <nav class="bg-white/80 backdrop-blur-md shadow-sm sticky top-0 z-50 border-b border-pink-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <h1 class="font-playfair text-3xl font-bold bg-gradient-to-r from-pink-500 to-rose-500 bg-clip-text text-transparent">
                    Cronette
                </h1>
                <div class="hidden md:flex space-x-8">
                    <a href="#home" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Home</a>
                    <a href="#about" class="nav-link text-gray-700 hover:text-pink-500 font-medium">About</a>
                    <a href="#products" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Products</a>
                    <a href="#contact" class="nav-link text-gray-700 hover:text-pink-500 font-medium">Contact</a>
                </div>
                <button id="mobile-menu-btn" class="md:hidden p-2 rounded-md text-gray-700 hover:text-pink-500">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                    </svg>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t border-pink-100">
            <div class="px-4 py-2 space-y-2">
                <a href="#home" class="block py-2 text-gray-700 hover:text-pink-500">Home</a>
                <a href="#about" class="block py-2 text-gray-700 hover:text-pink-500">About</a>
                <a href="#products" class="block py-2 text-gray-700 hover:text-pink-500">Products</a>
                <a href="#contact" class="block py-2 text-gray-700 hover:text-pink-500">Contact</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-pattern py-20 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <div class="floating">
                <div class="text-6xl mb-6">🧶</div>
            </div>
            <h2 class="font-playfair text-5xl md:text-6xl font-bold text-gray-800 mb-6 fade-in">
                Handcrafted with
                <span class="bg-gradient-to-r from-pink-500 to-rose-500 bg-clip-text text-transparent">Love</span>
            </h2>
            <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto leading-relaxed fade-in">
                Cronette creates unique and beautiful dresses - each a unique piece of art that showcases the skills and creativity of the maker.
            </p>
            <button class="bg-gradient-to-r from-pink-500 to-rose-500 text-white px-8 py-4 rounded-full font-semibold text-lg hover:from-pink-600 hover:to-rose-600 transform hover:scale-105 transition-all duration-300 shadow-lg hover:shadow-xl">
                Explore Collection
            </button>
        </div>
    </section>

    <!-- Features Section -->
    <section id="about" class="py-20 px-4 bg-white">
        <div class="max-w-6xl mx-auto">
            <h3 class="font-playfair text-4xl font-bold text-center text-gray-800 mb-16">
                Why Choose Cronette?
            </h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="card-hover bg-gradient-to-br from-pink-50 to-rose-50 p-8 rounded-2xl border border-pink-100">
                    <div class="text-4xl mb-4">✨</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">One of a Kind</h4>
                    <p class="text-gray-600 leading-relaxed">Each dress is carefully crafted by hand, making it a truly one-of-kind piece that you won't find anywhere else.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-orange-50 to-pink-50 p-8 rounded-2xl border border-orange-100">
                    <div class="text-4xl mb-4">💝</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Attention to Detail</h4>
                    <p class="text-gray-600 leading-relaxed">The maker puts love and care into every stitch, ensuring a high level of quality and attention to detail.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-purple-50 to-pink-50 p-8 rounded-2xl border border-purple-100">
                    <div class="text-4xl mb-4">📏</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Customizable</h4>
                    <p class="text-gray-600 leading-relaxed">Hand-made crochet dresses can be tailored to fit the wearer's specific measurements and style preferences.</p>
                </div>
                
                <div class="card-hover bg-gradient-to-br from-green-50 to-emerald-50 p-8 rounded-2xl border border-green-100">
                    <div class="text-4xl mb-4">🌱</div>
                    <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-3">Sustainable</h4>
                    <p class="text-gray-600 leading-relaxed">Crochet dresses made from eco-friendly yarns are a sustainable alternative to fast fashion.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Products Section -->
    <section id="products" class="py-20 px-4 crochet-pattern">
        <div class="max-w-6xl mx-auto">
            <h3 class="font-playfair text-4xl font-bold text-center text-gray-800 mb-16">
                Featured Collection
            </h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-pink-200 to-rose-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Summer Breeze Dress</h4>
                        <p class="text-gray-600 mb-4">Light and airy crochet dress perfect for warm days</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵450</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-purple-200 to-pink-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Elegant Evening Dress</h4>
                        <p class="text-gray-600 mb-4">Sophisticated design for special occasions</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵650</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="card-hover bg-white rounded-2xl overflow-hidden shadow-lg border border-gray-100">
                    <div class="h-64 bg-gradient-to-br from-orange-200 to-pink-300 flex items-center justify-center">
                        <div class="text-6xl">👗</div>
                    </div>
                    <div class="p-6">
                        <h4 class="font-playfair text-xl font-semibold text-gray-800 mb-2">Bohemian Maxi Dress</h4>
                        <p class="text-gray-600 mb-4">Free-spirited design with intricate patterns</p>
                        <div class="flex justify-between items-center">
                            <span class="text-2xl font-bold text-pink-500">₵550</span>
                            <button class="bg-pink-500 text-white px-4 py-2 rounded-full hover:bg-pink-600 transition-colors">
                                View Details
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4 bg-gradient-to-br from-pink-500 to-rose-500 text-white">
        <div class="max-w-4xl mx-auto text-center">
            <h3 class="font-playfair text-4xl font-bold mb-8">Get in Touch</h3>
            <p class="text-xl mb-12 opacity-90">Ready to create your perfect dress? Let's bring your vision to life!</p>
            
            <div class="grid md:grid-cols-3 gap-8 mb-12">
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📧</div>
                    <h4 class="font-semibold mb-2">Email Us</h4>
                    <p class="opacity-90">hello@cronette.com</p>
                </div>
                
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📱</div>
                    <h4 class="font-semibold mb-2">Call Us</h4>
                    <p class="opacity-90">+233 53 597 7147</p>
                </div>
                
                <div class="bg-white/10 backdrop-blur-sm p-6 rounded-2xl">
                    <div class="text-3xl mb-4">📍</div>
                    <h4 class="font-semibold mb-2">Visit Us</h4>
                    <p class="opacity-90">Tema, Ghana</p>
                </div>
            </div>
            
            <button class="bg-white text-pink-500 px-8 py-4 rounded-full font-semibold text-lg hover:bg-gray-50 transform hover:scale-105 transition-all duration-300 shadow-lg">
                Start Your Custom Order
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12 px-4">
        <div class="max-w-6xl mx-auto text-center">
            <h1 class="font-playfair text-3xl font-bold mb-4 bg-gradient-to-r from-pink-400 to-rose-400 bg-clip-text text-transparent">
                Cronette
            </h1>
            <p class="text-gray-400 mb-6">Handcrafted crochet dresses made with love</p>
            <div class="flex justify-center space-x-6 mb-8">
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M24 4.557c-.883.392-1.832.656-2.828.775 1.017-.609 1.798-1.574 2.165-2.724-.951.564-2.005.974-3.127 1.195-.897-.957-2.178-1.555-3.594-1.555-3.179 0-5.515 2.966-4.797 6.045-4.091-.205-7.719-2.165-10.148-5.144-1.29 2.213-.669 5.108 1.523 6.574-.806-.026-1.566-.247-2.229-.616-.054 2.281 1.581 4.415 3.949 4.89-.693.188-1.452.232-2.224.084.626 1.956 2.444 3.379 4.6 3.419-2.07 1.623-4.678 2.348-7.29 2.04 2.179 1.397 4.768 2.212 7.548 2.212 9.142 0 14.307-7.721 13.995-14.646.962-.695 1.797-1.562 2.457-2.549z"/>
                    </svg>
                </a>
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12.017 0C5.396 0 .029 5.367.029 11.987c0 5.079 3.158 9.417 7.618 11.174-.105-.949-.199-2.403.041-3.439.219-.937 1.406-5.957 1.406-5.957s-.359-.72-.359-1.781c0-1.663.967-2.911 2.168-2.911 1.024 0 1.518.769 1.518 1.688 0 1.029-.653 2.567-.992 3.992-.285 1.193.6 2.165 1.775 2.165 2.128 0 3.768-2.245 3.768-5.487 0-2.861-2.063-4.869-5.008-4.869-3.41 0-5.409 2.562-5.409 5.199 0 1.033.394 2.143.889 2.741.097.118.112.221.085.345-.09.375-.293 1.199-.334 1.363-.053.225-.172.271-.402.165-1.495-.69-2.433-2.878-2.433-4.646 0-3.776 2.748-7.252 7.92-7.252 4.158 0 7.392 2.967 7.392 6.923 0 4.135-2.607 7.462-6.233 7.462-1.214 0-2.357-.629-2.748-1.378l-.748 2.853c-.271 1.043-1.002 2.35-1.492 3.146C9.57 23.812 10.763 24.009 12.017 24.009c6.624 0 11.99-5.367 11.99-11.988C24.007 5.367 18.641.001.012.001z.017 0z"/>
                    </svg>
                </a>
                <a href="#" class="text-gray-400 hover:text-pink-400 transition-colors">
                    <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                        <path d="M12 2.163c3.204 0 3.584.012 4.85.07 3.252.148 4.771 1.691 4.919 4.919.058 1.265.069 1.645.069 4.849 0 3.205-.012 3.584-.069 4.849-.149 3.225-1.664 4.771-4.919 4.919-1.266.058-1.644.07-4.85.07-3.204 0-3.584-.012-4.849-.07-3.26-.149-4.771-1.699-4.919-4.92-.058-1.265-.07-1.644-.07-4.849 0-3.204.013-3.583.07-4.849.149-3.227 1.664-4.771 4.919-4.919 1.266-.057 1.645-.069 4.849-.069zm0-2.163c-3.259 0-3.667.014-4.947.072-4.358.2-6.78 2.618-6.98 6.98-.059 1.281-.073 1.689-.073 4.948 0 3.259.014 3.668.072 4.948.2 4.358 2.618 6.78 6.98 6.98 1.281.058 1.689.072 4.948.072 3.259 0 3.668-.014 4.948-.072 4.354-.2 6.782-2.618 6.979-6.98.059-1.28.073-1.689.073-4.948 0-3.259-.014-3.667-.072-4.947-.196-4.354-2.617-6.78-6.979-6.98-1.281-.059-1.69-.073-4.949-.073zm0 5.838c-3.403 0-6.162 2.759-6.162 6.162s2.759 6.163 6.162 6.163 6.162-2.759 6.162-6.163c0-3.403-2.759-6.162-6.162-6.162zm0 10.162c-2.209 0-4-1.79-4-4 0-2.209 1.791-4 4-4s4 1.791 4 4c0 2.21-1.791 4-4 4zm6.406-11.845c-.796 0-1.441.645-1.441 1.44s.645 1.44 1.441 1.44c.795 0 1.439-.645 1.439-1.44s-.644-1.44-1.439-1.44z"/>
                    </svg>
                </a>
            </div>
            <p class="text-gray-500 text-sm">© 2024 Cronette. All rights reserved. Made with 💖 and lots of yarn.</p>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    target.scrollIntoView({
                        behavior: 'smooth',
                        block: 'start'
                    });
                    // Close mobile menu if open
                    mobileMenu.classList.add('hidden');
                }
            });
        });

        // Add scroll effect to navigation
        window.addEventListener('scroll', () => {
            const nav = document.querySelector('nav');
            if (window.scrollY > 100) {
                nav.classList.add('bg-white/90');
            } else {
                nav.classList.remove('bg-white/90');
            }
        });

        // Add click functionality to buttons
        document.querySelectorAll('button').forEach(button => {
            if (button.textContent.includes('Explore Collection')) {
                button.addEventListener('click', () => {
                    document.getElementById('products').scrollIntoView({
                        behavior: 'smooth'
                    });
                });
            } else if (button.textContent.includes('View Details')) {
                button.addEventListener('click', () => {
                    alert('Product details coming soon! Contact us for more information.');
                });
            } else if (button.textContent.includes('Start Your Custom Order')) {
                button.addEventListener('click', () => {
                    alert('Thank you for your interest! We\'ll be in touch soon to discuss your custom order.');
                });
            }
        });

        // Add fade-in animation on scroll
        const observerOptions = {
            threshold: 0.1,
            rootMargin: '0px 0px -50px 0px'
        };

        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('fade-in');
                }
            });
        }, observerOptions);

        // Observe all cards and sections
        document.querySelectorAll('.card-hover, section').forEach(el => {
            observer.observe(el);
        });
    </script>
</body>
<img src="https://your-image![IMG-20250824-WA0233](https://github.com/user-attachments/assets/84257683-9303-4631-b957-4c9abaa36dc5)

</html>
