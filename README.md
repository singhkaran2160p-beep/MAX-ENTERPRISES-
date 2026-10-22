# MAX-ENTERPRISES-
Max Enterprises – Quality Cleaning &amp; Hygiene Solutions Max Enterprises delivers high-performance cleaning solutions for homes, offices, hotels, and industrial spaces. We manufacture and supply premium phenyl, powerful dishwash liquids, floor cleaners, and surface sanitizers designed for deep cleaning, germ protection, and long-lasting freshness.
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Max Enterprises | Pure Hygiene, Maximum Shine</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Lucide Icons -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <!-- Google Fonts Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['"Plus Jakarta Sans"', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            50: '#eff9fc',
                            100: '#daf1f8',
                            200: '#b9e4f2',
                            500: '#0284c7', // vibrant cyan/blue
                            600: '#0369a1',
                            700: '#075985',
                        },
                        mint: {
                            50: '#f0fdf4',
                            100: '#dcfce7',
                            500: '#10b981',
                            600: '#059669',
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .glass-card {
            background: rgba(255, 255, 255, 0.92);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(226, 232, 240, 0.8);
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-brand-500 selection:text-white flex flex-col min-h-screen">

    <!-- Top Info Bar -->
    <div class="bg-gradient-to-r from-brand-700 via-brand-600 to-teal-700 text-white text-xs sm:text-sm py-2 px-4 shadow-sm">
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row justify-between items-center gap-2">
            <div class="flex items-center gap-4">
                <span class="flex items-center gap-1.5"><i data-lucide="shield-check" class="w-4 h-4 text-emerald-300"></i> ISO Compliant & Eco-friendly Formulas</span>
                <span class="hidden md:inline text-slate-300">|</span>
                <span class="hidden md:flex items-center gap-1.5"><i data-lucide="truck" class="w-4 h-4 text-amber-300"></i> Wholesale & Bulk Supply Available Across India</span>
            </div>
            <div class="flex items-center gap-4">
                <a href="tel:+919876543210" class="hover:text-emerald-200 transition-colors flex items-center gap-1">
                    <i data-lucide="phone-call" class="w-3.5 h-3.5"></i> +91 98765 43210
                </a>
                <span class="text-slate-300">|</span>
                <span class="text-xs bg-emerald-500/20 text-emerald-200 px-2 py-0.5 rounded-full font-medium border border-emerald-400/30">Direct Manufacturer</span>
            </div>
        </div>
    </div>

    <!-- Navigation Header -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200/80 shadow-xs">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo -->
            <a href="#" class="flex items-center gap-3 group">
                <div class="w-11 h-11 rounded-xl bg-gradient-to-tr from-brand-600 to-teal-500 flex items-center justify-center text-white shadow-md shadow-brand-500/20 group-hover:scale-105 transition-transform duration-300">
                    <i data-lucide="sparkles" class="w-6 h-6"></i>
                </div>
                <div>
                    <span class="text-xl sm:text-2xl font-extrabold tracking-tight text-slate-900 block leading-tight">
                        MAX <span class="text-brand-600">ENTERPRISES</span>
                    </span>
                    <span class="text-[11px] font-semibold tracking-wider uppercase text-teal-600 block">Pure Hygiene • Maximum Shine</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden lg:flex items-center gap-8 font-medium text-slate-600">
                <a href="#home" class="hover:text-brand-600 transition-colors">Home</a>
                <a href="#about" class="hover:text-brand-600 transition-colors">About Us</a>
                <a href="#products" class="hover:text-brand-600 transition-colors">Products</a>
                <a href="#why-us" class="hover:text-brand-600 transition-colors">Why Choose Us</a>
                <a href="#testimonials" class="hover:text-brand-600 transition-colors">Client Reviews</a>
                <a href="#contact" class="hover:text-brand-600 transition-colors">Bulk Inquiry</a>
            </nav>

            <!-- Quick Action CTA -->
            <div class="hidden sm:flex items-center gap-3">
                <a href="#products" class="px-4 py-2 text-sm font-semibold text-brand-700 bg-brand-50 hover:bg-brand-100 rounded-lg transition-colors border border-brand-200">
                    View Catalog
                </a>
                <button onclick="openWhatsAppModal()" class="px-4 py-2 text-sm font-semibold text-white bg-emerald-600 hover:bg-emerald-700 rounded-lg shadow-sm hover:shadow transition-all flex items-center gap-2">
                    <i data-lucide="message-circle" class="w-4 h-4"></i>
                    WhatsApp Order
                </button>
            </div>

            <!-- Mobile Hamburger -->
            <button id="mobileMenuBtn" class="lg:hidden p-2 rounded-lg text-slate-600 hover:text-slate-900 hover:bg-slate-100">
                <i data-lucide="menu" class="w-6 h-6"></i>
            </button>
        </div>

        <!-- Mobile Drawer -->
        <div id="mobileMenu" class="hidden lg:hidden border-t border-slate-200 bg-white px-4 pt-3 pb-5 space-y-3 shadow-lg">
            <a href="#home" class="block py-2 text-slate-700 font-medium hover:text-brand-600" onclick="toggleMobileMenu()">Home</a>
            <a href="#about" class="block py-2 text-slate-700 font-medium hover:text-brand-600" onclick="toggleMobileMenu()">About Us</a>
            <a href="#products" class="block py-2 text-slate-700 font-medium hover:text-brand-600" onclick="toggleMobileMenu()">Products</a>
            <a href="#why-us" class="block py-2 text-slate-700 font-medium hover:text-brand-600" onclick="toggleMobileMenu()">Why Choose Us</a>
            <a href="#contact" class="block py-2 text-slate-700 font-medium hover:text-brand-600" onclick="toggleMobileMenu()">Bulk Inquiry</a>
            <button onclick="openWhatsAppModal(); toggleMobileMenu();" class="w-full mt-2 py-2.5 px-4 bg-emerald-600 hover:bg-emerald-700 text-white font-semibold rounded-lg text-center flex justify-center items-center gap-2">
                <i data-lucide="message-circle" class="w-5 h-5"></i> Quick WhatsApp Order
            </button>
        </div>
    </header>

    <!-- Main Content -->
    <main class="flex-grow">
        <!-- Hero Section -->
        <section id="home" class="relative overflow-hidden pt-12 pb-20 lg:pt-20 lg:pb-28 bg-gradient-to-b from-brand-50/70 via-white to-slate-50">
            <!-- Decorative Background Blobs -->
            <div class="absolute -top-32 -left-32 w-96 h-96 bg-brand-200/40 rounded-full blur-3xl pointer-events-none"></div>
            <div class="absolute top-1/2 -right-32 w-96 h-96 bg-teal-200/40 rounded-full blur-3xl pointer-events-none"></div>

            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-12 items-center">
                    
                    <!-- Left Hero Text -->
                    <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                        <div class="inline-flex items-center gap-2 px-3.5 py-1.5 rounded-full bg-emerald-100 text-emerald-800 text-xs sm:text-sm font-semibold tracking-wide border border-emerald-300">
                            <span class="w-2 h-2 rounded-full bg-emerald-500 animate-ping"></span>
                            Trusted Commercial & Household Cleaning Range
                        </div>
                        
                        <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold tracking-tight text-slate-900 leading-[1.15]">
                            Pure Hygiene, <br class="hidden sm:inline" />
                            <span class="text-transparent bg-clip-text bg-gradient-to-r from-brand-600 via-teal-600 to-emerald-600">Maximum Shine.</span>
                        </h1>

                        <p class="text-base sm:text-lg text-slate-600 max-w-2xl mx-auto lg:mx-0 leading-relaxed">
                            Max Enterprises supplies high-potency, safe, and hospital-grade cleaning liquids. From concentrated white phenyl and degreasing dishwash gels to sparkling floor & glass cleaners — available in retail & wholesale bulk packs.
                        </p>

                        <!-- CTA Row -->
                        <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
                            <a href="#products" class="w-full sm:w-auto px-7 py-3.5 bg-brand-600 hover:bg-brand-700 text-white font-semibold rounded-xl shadow-lg shadow-brand-500/25 transition-all text-center flex items-center justify-center gap-2">
                                <i data-lucide="package-search" class="w-5 h-5"></i>
                                Explore Catalog
                            </a>
                            <button onclick="openWhatsAppModal()" class="w-full sm:w-auto px-7 py-3.5 bg-emerald-600 hover:bg-emerald-700 text-white font-semibold rounded-xl shadow-md shadow-emerald-600/20 transition-all text-center flex items-center justify-center gap-2">
                                <i data-lucide="message-square" class="w-5 h-5"></i>
                                Order via WhatsApp
                            </button>
                        </div>

                        <!-- Highlights Badges -->
                        <div class="pt-6 border-t border-slate-200/80 grid grid-cols-3 gap-4 text-center sm:text-left">
                            <div>
                                <h3 class="text-2xl font-bold text-slate-900">99.9%</h3>
                                <p class="text-xs text-slate-500 font-medium">Germ & Bacteria Kill</p>
                            </div>
                            <div>
                                <h3 class="text-2xl font-bold text-slate-900">500+</h3>
                                <p class="text-xs text-slate-500 font-medium">B2B Clients & Offices</p>
                            </div>
                            <div>
                                <h3 class="text-2xl font-bold text-slate-900">Direct</h3>
                                <p class="text-xs text-slate-500 font-medium">Wholesale Pricing</p>
                            </div>
                        </div>
                    </div>

                    <!-- Right Hero Visual Card -->
                    <div class="lg:col-span-5 relative">
                        <div class="relative mx-auto max-w-md lg:max-w-none rounded-2xl bg-gradient-to-tr from-brand-600 to-teal-500 p-1 shadow-2xl">
                            <div class="bg-white rounded-[15px] p-6 sm:p-8 space-y-6">
                                <div class="flex items-center justify-between border-b border-slate-100 pb-4">
                                    <span class="text-xs uppercase font-bold tracking-wider text-brand-600 bg-brand-50 px-2.5 py-1 rounded-md">Best Seller Cans</span>
                                    <div class="flex text-amber-400">
                                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                                        <i data-lucide="star" class="w-4 h-4 fill-amber-400"></i>
                                    </div>
                                </div>

                                <!-- Feature Product Visual Representation (SVG Graphics) -->
                                <div class="h-56 bg-gradient-to-b from-brand-50 to-slate-100 rounded-xl flex items-center justify-center relative overflow-hidden border border-brand-100/60 p-4">
                                    <!-- Dynamic Animated cleaning illustration -->
                                    <div class="flex items-end justify-center gap-4">
                                        <!-- Floor Cleaner Bottle SVG -->
                                        <div class="text-center group">
                                            <div class="w-16 h-28 bg-emerald-500 rounded-t-lg rounded-b-xl relative shadow-md flex items-center justify-center text-white font-bold text-xs">
                                                <div class="absolute -top-3 w-6 h-3 bg-slate-700 rounded-t-sm"></div>
                                                <div class="text-center leading-none">
                                                    <i data-lucide="shield" class="w-5 h-5 mx-auto mb-1"></i>
                                                    Phenyl
                                                </div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-600 mt-1 block">Pine / Herbal</span>
                                        </div>
                                        <!-- Main 5L Bulk Canister SVG -->
                                        <div class="text-center">
                                            <div class="w-24 h-36 bg-brand-600 rounded-t-xl rounded-b-2xl relative shadow-lg flex flex-col items-center justify-center text-white font-bold text-xs">
                                                <div class="absolute -top-3 w-8 h-3 bg-amber-400 rounded-t-sm"></div>
                                                <div class="w-5 h-8 border-2 border-white rounded-r-md absolute -left-5 top-8"></div>
                                                <i data-lucide="sparkles" class="w-6 h-6 mb-1 text-teal-200"></i>
                                                <span class="text-xs uppercase tracking-wider font-extrabold">MAX 5L</span>
                                                <span class="text-[10px] font-normal text-brand-100">Floor Disinfectant</span>
                                            </div>
                                            <span class="text-[11px] font-bold text-brand-700 mt-1 block">5 Litre Economy</span>
                                        </div>
                                        <!-- Dishwash Gel SVG -->
                                        <div class="text-center">
                                            <div class="w-14 h-24 bg-amber-500 rounded-t-full rounded-b-lg relative shadow-md flex items-center justify-center text-white font-bold text-xs">
                                                <div class="absolute -top-2 w-4 h-2 bg-slate-800"></div>
                                                <div class="text-center leading-none">
                                                    <i data-lucide="droplet" class="w-4 h-4 mx-auto mb-0.5"></i>
                                                    Dishwash
                                                </div>
                                            </div>
                                            <span class="text-[10px] font-semibold text-slate-600 mt-1 block">Lime Cut</span>
                                        </div>
                                    </div>
                                    <div class="absolute bottom-2 right-2 bg-white/90 backdrop-blur-xs px-2 py-1 rounded text-[11px] font-bold text-slate-700 shadow-xs">
                                        500ml | 1L | 5L
                                    </div>
                                </div>

                                <div class="space-y-2 text-sm text-slate-600">
                                    <div class="flex items-center gap-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-600"></i> Concentrated formula for maximum savings</div>
                                    <div class="flex items-center gap-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-600"></i> Pleasant long-lasting pine, lemon & citrus fragrance</div>
                                    <div class="flex items-center gap-2"><i data-lucide="check-circle-2" class="w-4 h-4 text-emerald-600"></i> Perfect for Tiles, Granite, Marble & Ceramics</div>
                                </div>

                                <button onclick="selectProductToOrder('Floor Cleaner 5L Can')" class="w-full py-2.5 bg-slate-900 hover:bg-slate-800 text-white text-sm font-semibold rounded-lg transition-colors flex items-center justify-center gap-2">
                                    <i data-lucide="shopping-bag" class="w-4 h-4"></i> Instant Quote for 5L Cans
                                </button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- About Us Section -->
        <section id="about" class="py-16 bg-white border-y border-slate-200/80">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                    <div>
                        <span class="text-xs font-bold uppercase tracking-wider text-teal-600 bg-teal-50 px-3 py-1 rounded-full border border-teal-200">About Max Enterprises</span>
                        <h2 class="mt-3 text-3xl sm:text-4xl font-extrabold text-slate-900 tracking-tight leading-tight">
                            Elevating Cleanliness with Scientific & Reliable Hygiene Formulations
                        </h2>
                        <p class="mt-4 text-slate-600 text-base leading-relaxed">
                            Established with the vision to deliver hospital-grade cleanliness at fair pricing, <strong>Max Enterprises</strong> is a premier manufacturer and distributor of hygiene essentials. We formulate heavy-duty cleaners that eliminate grease, grime, and hazardous pathogens without harming your surfaces or hands.
                        </p>
                        <p class="mt-3 text-slate-600 text-base leading-relaxed">
                            Whether you need daily cleaning solutions for households or high-volume wholesale supplies for corporate complexes, hotels, clinics, schools, and banquet halls, we provide tailored bulk packaging with guaranteed quality consistency.
                        </p>

                        <div class="mt-8 grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div class="p-4 rounded-xl bg-slate-50 border border-slate-100 flex items-start gap-3">
                                <div class="p-2 rounded-lg bg-emerald-100 text-emerald-700 shrink-0">
                                    <i data-lucide="leaf" class="w-5 h-5"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-slate-800 text-sm">Eco-Conscious</h4>
                                    <p class="text-xs text-slate-500 mt-0.5"
