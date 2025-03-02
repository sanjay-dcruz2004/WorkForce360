<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WorkForce360 - Modern Employee Management System</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.1/font/bootstrap-icons.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .hero {
            background: linear-gradient(135deg, #43cea2 0%, #185a9d 100%);
        }
        .feature-card:hover {
            transform: translateY(-5px);
            transition: all 0.3s ease;
        }
        @media (max-width: 768px) {
            .hero {
                text-align: center;
            }
        }
    </style>
</head>
<body>
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="container mx-auto px-4">
            <div class="flex justify-between items-center py-4">
                <div class="flex items-center">
                    <i class="bi bi-building text-teal-600 text-3xl mr-2"></i>
                    <span class="font-bold text-xl text-gray-800">WorkForce360</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="/login" class="text-teal-600 font-medium">Login</a>
                    <a href="/signup" class="bg-teal-600 text-white px-4 py-2 rounded-lg hover:bg-teal-700 transition">
                        Get Started
                    </a>
                </div>
                <button class="md:hidden text-gray-600">
                    <i class="bi bi-list text-2xl"></i>
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="hero pt-32 pb-20 px-4">
        <div class="container mx-auto">
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 text-white">
                    <h1 class="text-4xl md:text-5xl font-bold mb-6">
                        Streamline Your Workforce Management
                    </h1>
                    <p class="text-lg mb-8 opacity-90">
                        An all-in-one platform for attendance tracking, leave management, and performance evaluation. 
                        Empower your HR team and employees with modern tools.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="HR_signup.html" class="bg-teal-600 text-white px-8 py-3 rounded-lg font-medium text-center hover:bg-teal-700 transition">
                            Start Your Experience Today
                        </a>
                    </div>
                </div>
                <div class="md:w-1/2 mt-12 md:mt-0">
                    <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80" 
                         alt="Dashboard Preview" 
                         class="rounded-lg shadow-2xl">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section id="features" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gray-800 mb-4">
                    Powerful Features for Modern Workplaces
                </h2>
                <p class="text-gray-600 max-w-2xl mx-auto">
                    Everything you need to manage your workforce effectively, all in one place.
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Attendance Tracking -->
                <div class="feature-card bg-white p-6 rounded-lg shadow-lg">
                    <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="bi bi-clock text-2xl text-teal-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Attendance Tracking</h3>
                    <p class="text-gray-600">
                        Real-time attendance monitoring with geolocation support and automated reports.
                    </p>
                </div>

                <!-- Leave Management -->
                <div class="feature-card bg-white p-6 rounded-lg shadow-lg">
                    <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="bi bi-calendar-check text-2xl text-teal-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Leave Management</h3>
                    <p class="text-gray-600">
                        Streamlined leave requests and approvals with balance tracking.
                    </p>
                </div>

                <!-- Performance Evaluation -->
                <div class="feature-card bg-white p-6 rounded-lg shadow-lg">
                    <div class="w-12 h-12 bg-teal-100 rounded-lg flex items-center justify-center mb-4">
                        <i class="bi bi-graph-up text-2xl text-teal-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Performance Tracking</h3>
                    <p class="text-gray-600">
                        Comprehensive performance metrics and evaluation tools.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-20 bg-teal-600 text-white">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div>
                    <div class="text-4xl font-bold mb-2">5000+</div>
                    <div class="text-teal-100">Companies</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">1M+</div>
                    <div class="text-teal-100">Employees</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">99.9%</div>
                    <div class="text-teal-100">Uptime</div>
                </div>
                <div>
                    <div class="text-4xl font-bold mb-2">24/7</div>
                    <div class="text-teal-100">Support</div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl font-bold mb-8">Ready to Transform Your Workforce Management?</h2>
            <div class="flex justify-center gap-4">
                <a href="/signup" class="bg-teal-600 text-white px-8 py-3 rounded-lg font-medium hover:bg-teal-700 transition">
                    Get Started Now
                </a>
                <a href="/contact" class="bg-gray-100 text-gray-800 px-8 py-3 rounded-lg font-medium hover:bg-gray-200 transition">
                    Contact Sales
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-gray-300 py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-white font-bold mb-4">WorkForce360</h3>
                    <p class="text-sm">
                        Modern solutions for modern workplaces. Streamline your HR operations with our comprehensive platform.
                    </p>
                </div>
                <div>
                    <h4 class="text-white font-semibold mb-4">Product</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#" class="hover:text-white">Features</a></li>
                        <li><a href="#" class="hover:text-white">Pricing</a></li>
                        <li><a href="#" class="hover:text-white">Security</a></li>
                        <li><a href="#" class="hover:text-white">Enterprise</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-semibold mb-4">Company</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#" class="hover:text-white">About</a></li>
                        <li><a href="#" class="hover:text-white">Careers</a></li>
                        <li><a href="#" class="hover:text-white">Blog</a></li>
                        <li><a href="#" class="hover:text-white">Contact</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-white font-semibold mb-4">Legal</h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#" class="hover:text-white">Privacy</a></li>
                        <li><a href="#" class="hover:text-white">Terms</a></li>
                        <li><a href="#" class="hover:text-white">Security</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-700 mt-8 pt-8 text-sm text-center">
                <p>&copy; 2023 WorkForce360. All rights reserved.</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.querySelector('.md\\:hidden').addEventListener('click', function() {
            const mobileMenu = document.querySelector('.md\\:flex');
            mobileMenu.classList.toggle('hidden');
        });

        // Smooth scroll for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
