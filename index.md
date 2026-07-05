---
layout: page
title: Home | PhilPro Global
---
<!-- HERO MOTION STYLING (Left-Aligned Smooth Entrance) -->
<style>
    @keyframes smoothSlideLeft {
        0% {
            opacity: 0;
            transform: translateX(-30px);
        }
        100% {
            opacity: 1;
            transform: translateX(0);
        }
    }

    .animate-hero-left {
        opacity: 0;
        animation: smoothSlideLeft 1.2s cubic-bezier(0.16, 1, 0.3, 1) forwards;
    }
</style>

<!-- HERO BANNER SECTION (Left-Aligned, Full-Width - Prime Inspired) -->
<section class="relative bg-cover bg-center bg-no-repeat py-28 sm:py-36 px-6 sm:px-12 lg:px-20 flex items-center min-h-[650px] bg-[#050B14] overflow-hidden" 
         style="background-image: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1600&auto=format&fit=crop'); background-color: #050B14;">

    <!-- UPDATED: Brand-Aligned Deep Navy Overlay -->
<div class="absolute inset-0 bg-gradient-to-r from-[#001a4d]/95 via-[#002b80]/85 to-transparent z-10"></div>

    <!-- Content Container (Entire block slides together smoothly, aligned left) -->
    <div class="animate-hero-left relative max-w-7xl mx-auto w-full grid grid-cols-1 lg:grid-cols-12 z-10">
        
        <div class="lg:col-span-8 xl:col-span-7 text-left space-y-6">
            <!-- Premium Subtitle Tag (Left Aligned) -->
            <div class="flex items-center gap-3">
                <span class="w-8 h-[2px]" style="background-color: #E53E3E;"></span>
                <span class="text-sm sm:text-base font-black uppercase tracking-[0.15em]" style="color: #E53E3E !important;">
                    Accounting & Tax Outsourcing
                </span>
            </div>

            <!-- Balanced Main Heading (Left Aligned) -->
            <h1 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold leading-tight uppercase tracking-normal" 
                style="color: #FFFFFF !important; text-shadow: 0px 2px 4px rgba(0,0,0,0.4);">
                Reliable accounting, bookkeeping, and finance support for businesses worldwide.
            </h1>

            <!-- Crisp Secondary Body Copy (Left Aligned) -->
            <p class="text-base sm:text-lg leading-relaxed font-normal pt-1 max-w-2xl" 
               style="color: #E5E7EB !important; text-shadow: 0px 1px 2px rgba(0,0,0,0.4);">
                PhilPro is a Philippine-registered Business Process Outsourcing (BPO) company that helps accounting firms, SMEs, and growing businesses streamline their finance operations through experienced accounting professionals, secure processes, and scalable offshore solutions.
            </p>

            <!-- Strong Action Buttons (Left Aligned) -->
            <div class="flex flex-wrap gap-4 pt-4">
                <a href="/contact" class="text-base font-bold uppercase tracking-wider px-10 py-4 rounded hover:bg-white hover:text-[#051329] transition-colors duration-300 shadow-lg min-w-[180px] text-center"
                   style="color: #FFFFFF !important; background-color: #CC0000 !important;">
                    Get A Quote
                </a>
                <a href="/contact" class="bg-transparent border-2 border-white text-base font-bold uppercase tracking-wider px-10 py-4 rounded hover:bg-[#CC0000] hover:border-[#CC0000] transition-colors duration-300 shadow-lg min-w-[180px] text-center"
                   style="color: #FFFFFF !important; border-color: #FFFFFF !important;">
                    Inquire Now
                </a>
            </div>
        </div>
        
    </div>
</section>

<!-- WHY PHILPRO SECTION (Professionally Clean Light Gray with Dynamic Hover Interaction Cards) -->
<section class="bg-[#F4F6F9] py-24 px-8">
    <div class="max-w-7xl mx-auto">
        <div class="max-w-4xl mb-16 space-y-4" data-reveal="up">
            <!-- H2 is now the dominant title (4xl) -->
            <h2 class="text-[#003399] text-4xl font-black uppercase tracking-tight">Why PhilPro?</h2>
            <!-- H3 is now the sub-header (2xl) -->
            <h3 class="text-2xl font-black text-[#1A1A1A] uppercase">Your Offshore Accounting Team—Without the Overhead</h3>
            
            <p class="text-2xl text-[#333333] leading-relaxed pt-2">
                Finding qualified accounting talent is becoming increasingly difficult and expensive. PhilPro provides dedicated finance professionals who integrate seamlessly into your business, allowing you to reduce costs while maintaining quality and compliance.
            </p>
        </div>

        <!-- Premium Interactive Cards Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
            
            <!-- Card 1: Qualified Professionals -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1556761175-4b46a572b786?q=80&w=600&auto=format&fit=crop" 
                         alt="Qualified Accounting Professionals" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-user-tie fa-solid"></i></span>
                        Qualified Professionals
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Highly trained and certified accounting experts matched to your operational needs.</p>
                </div>
            </div>

            <!-- Card 2: Cost-Effective -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1554224154-26032ffc0d07?q=80&w=600&auto=format&fit=crop" 
                         alt="Cost-Effective Solutions" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-percentage fa-solid"></i></span>
                        Cost-Effective
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Drastically lower corporate overhead costs without sacrificing service quality.</p>
                </div>
            </div>

            <!-- Card 3: Secure Processes -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1563986768609-322da13575f3?q=80&w=600&auto=format&fit=crop" 
                         alt="Secure Data Processes" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-shield-alt fa-solid"></i></span>
                        Secure Processes
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Strict regulatory confidentiality standards to keep your client records protected.</p>
                </div>
            </div>

            <!-- Card 4: Flexible Scaling -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1460925895917-afdab827c52f?q=80&w=600&auto=format&fit=crop" 
                         alt="Flexible Scaling" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-chart-line fa-solid"></i></span>
                        Flexible Scaling
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Easily add operational capacity as your practice expands month over month.</p>
                </div>
            </div>

            <!-- Card 5: Fluent English -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1522071820081-009f0129c71c?q=80&w=600&auto=format&fit=crop" 
                         alt="Fluent Communications" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-comments fa-solid"></i></span>
                        Fluent English
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Clear, professional, and completely seamless daily corporate communications.</p>
                </div>
            </div>

            <!-- Card 6: Dedicated Support -->
            <div class="group bg-white rounded-lg border border-gray-200 shadow-sm overflow-hidden transition-all duration-300 hover:-translate-y-2 hover:shadow-xl" data-reveal="up">
                <div class="overflow-hidden aspect-[16/10] relative">
                    <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?q=80&w=600&auto=format&fit=crop" 
                         alt="Dedicated Corporate Support" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <div class="p-8">
                    <h4 class="text-2xl font-black text-[#1A1A1A] mb-3 uppercase tracking-wide group-hover:text-[#003399] transition-colors flex items-center gap-3">
                        <span class="text-[#003399] text-2xl"><i class="fas fa-headphones fa-solid"></i></span>
                        Dedicated Support
                    </h4>
                    <p class="text-xl text-[#333333] leading-relaxed">Continuous local account management ensuring peak workflow execution.</p>
                </div>
            </div>

        </div>
    </div>
</section>

<!-- SERVICES GRID SECTION -->
<section class="bg-white py-24 px-8">
    <div class="max-w-7xl mx-auto" data-reveal="up">
        <div class="mb-16 text-center lg:text-left">
            <span class="text-[#003399] text-xl font-bold uppercase tracking-widest block mb-2">Expert Solutions</span>
            <!-- H2: Standardized Size and Color -->
            <h2 class="text-[#1A1A1A] text-5xl font-black uppercase tracking-tight">Our Outsourcing Services</h2>
            <div class="w-24 h-1.5 bg-[#003399] mt-4 mx-auto lg:mx-0"></div>
        </div>

        <!-- 4-Column Image & Text Cards Grid -->
        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
            
            <!-- Service Card 1 -->
            <div class="group cursor-pointer">
                <div class="overflow-hidden rounded-md mb-4 aspect-[4/3] border border-gray-200 shadow-sm">
                    <img src="https://images.unsplash.com/photo-1554224155-8d04cb21cd6c?q=80&w=600&auto=format&fit=crop" 
                         alt="Accounting Services" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <!-- Forced blue via !text-[#003399] and forced hover via group-hover:!text-[#0066CC] -->
                <h3 class="text-2xl font-black !text-[#1A1A1A] group-hover:!text-[#0066CC] uppercase tracking-wide transition-colors duration-300 flex items-center justify-between">
                    Accounting Services
                    <span class="text-xl transform transition-transform duration-300 group-hover:translate-x-2"><i class="fas fa-arrow-right fa-solid"></i></span>
                </h3>
            </div>

            <!-- Service Card 2 -->
            <div class="group cursor-pointer">
                <div class="overflow-hidden rounded-md mb-4 aspect-[4/3] border border-gray-200 shadow-sm">
                    <img src="https://images.unsplash.com/photo-1544377193-33dcf4d68fb5?q=80&w=600&auto=format&fit=crop" 
                         alt="Tax Services" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <!-- Forced blue via !text-[#003399] and forced hover via group-hover:!text-[#0066CC] -->
                <h3 class="text-2xl font-black !text-[#1A1A1A] group-hover:!text-[#0066CC] uppercase tracking-wide transition-colors duration-300 flex items-center justify-between">
                    Tax Services
                    <span class="text-xl transform transition-transform duration-300 group-hover:translate-x-2"><i class="fas fa-arrow-right fa-solid"></i></span>
                </h3>
            </div>

            <!-- Service Card 3 -->
            <div class="group cursor-pointer">
                <div class="overflow-hidden rounded-md mb-4 aspect-[4/3] border border-gray-200 shadow-sm">
                    <img src="https://images.unsplash.com/photo-1486406146926-c627a92ad1ab?q=80&w=600&auto=format&fit=crop" 
                         alt="CPA Firms Support" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <!-- Forced blue via !text-[#003399] and forced hover via group-hover:!text-[#0066CC] -->
                <h3 class="text-2xl font-black !text-[#1A1A1A] group-hover:!text-[#0066CC] uppercase tracking-wide transition-colors duration-300 flex items-center justify-between">
                    CPA Firms
                    <span class="text-xl transform transition-transform duration-300 group-hover:translate-x-2"><i class="fas fa-arrow-right fa-solid"></i></span>
                </h3>
            </div>

            <!-- Service Card 4 -->
            <div class="group cursor-pointer">
                <div class="overflow-hidden rounded-md mb-4 aspect-[4/3] border border-gray-200 shadow-sm">
                    <img src="https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=600&auto=format&fit=crop" 
                         alt="Other Offshore Services" 
                         class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105">
                </div>
                <!-- Forced blue via !text-[#003399] and forced hover via group-hover:!text-[#0066CC] -->
                <h3 class="text-2xl font-black !text-[#1A1A1A] group-hover:!text-[#0066CC] uppercase tracking-wide transition-colors duration-300 flex items-center justify-between">
                    Other Offshore
                    <span class="text-xl transform transition-transform duration-300 group-hover:translate-x-2"><i class="fas fa-arrow-right fa-solid"></i></span>
                </h3>
            </div>

        </div>
    </div>
</section>

<section class="bg-white py-16 px-6 sm:px-12 lg:px-20 font-sans">
    <div class="max-w-7xl mx-auto">
        <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 lg:gap-12 items-baseline pb-6">
            <div class="lg:col-span-4">
                <!-- H2: Standardized Size and Color -->
                <h2 class="text-[#003399] text-3xl font-black uppercase tracking-wide">Industries We Serve</h2>
            </div>
            <div class="lg:col-span-8">
                <p class="text-base text-gray-600 font-normal">We deliver customized, secure, and highly scalable back-office finance systems tailored to meet the unique compliance frameworks and operational demands of diverse global sectors.</p>
            </div>
        </div>
        <div class="w-full h-[1px] bg-gray-200 mb-8"></div>

        <!-- Bottom Block: Tight, Clean List Grid -->
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-y-4 gap-x-8">
            
            <!-- Item 1 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Accounting Firms</span>
            </div>

            <!-- Item 2 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Professional Services</span>
            </div>

            <!-- Item 3 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">E-commerce</span>
            </div>

            <!-- Item 4 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Real Estate</span>
            </div>

            <!-- Item 5 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Healthcare</span>
            </div>

            <!-- Item 6 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Construction</span>
            </div>

            <!-- Item 7 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Technology Companies</span>
            </div>

            <!-- Item 8 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Startups</span>
            </div>

            <!-- Item 9 -->
            <div class="flex items-center gap-3 py-2 border-b border-gray-50">
                <span class="w-1.5 h-1.5 bg-gray-400 rounded-full"></span>
                <span class="text-base font-medium text-gray-800">Nonprofit Organizations</span>
            </div>

        </div>
    </div>
</section>

<!-- STRATEGIC ADVANTAGE: WHY THE PHILIPPINES (Map Silhouette Design) -->
<section class="relative bg-[#EDF4FF] py-24 px-8 text-center overflow-hidden">

    <!-- Philippines Map Watermark -->
    <div class="absolute inset-0 z-0 flex items-center justify-center opacity-[0.04] pointer-events-none">
        <svg viewBox="0 0 400 600" xmlns="http://www.w3.org/2000/svg" class="h-full w-auto">
            <!-- Simplified Philippine Map Outline -->
            <path d="M220 50 L240 80 L230 110 L250 140 L220 180 L200 220 L180 250 L150 240 L130 280 L160 320 L140 360 L170 400 L150 440 L180 480 L160 520 L190 560 L210 520 L240 480 L220 440 L250 400 L280 360 L300 320 L280 280 L320 240 L350 200 L320 160 L300 120 L280 80 L260 40 Z" fill="#003399" />
        </svg>
    </div>

    <!-- Content -->
    <div class="relative z-10 max-w-4xl mx-auto space-y-8">
        <div class="space-y-3" data-reveal="up">
            <span class="text-[#003399] text-xl font-bold uppercase tracking-widest block">
                <i class="fas fa-globe-asia fa-solid mr-2"></i> Strategic Advantage
            </span>
            <h2 class="text-[#003399] text-5xl font-black uppercase leading-tight">
                Why The Philippines?
            </h2>
            <div class="w-20 h-1.5 bg-[#003399] mx-auto"></div>
        </div>

        <div class="space-y-6 text-xl text-[#333333] leading-relaxed font-normal max-w-3xl mx-auto" data-reveal="up">
            <p>
                The Philippines has earned its reputation as one of the world's premier destinations for financial and corporate outsourcing. By centralizing operations here, businesses tap into an exceptionally deep pool of CPA-qualified talent and seasoned finance professionals.
            </p>
            <p>
                Beyond technical proficiency, our professionals offer outstanding English fluency, a high cultural alignment with global business practices, and a strong customer-first mindset. This ensures your offshore team communicates smoothly and integrates flawlessly into your daily workflows.
            </p>
        </div>
    </div>
</section>
<section class="bg-white py-20 px-6 sm:px-12 lg:px-20 font-sans overflow-hidden">

    <style>
        @keyframes strokeFlow {
            0% {
                stroke-dashoffset: 60;
            }
            100% {
                stroke-dashoffset: 0;
            }
        }
        .animate-arrow-flow {
            stroke-dasharray: 12 8;
            animation: strokeFlow 4s linear infinite;
        }
    </style>

    <div class="max-w-7xl mx-auto text-center">

        <h2 class="text-3xl sm:text-4xl lg:text-5xl font-extrabold tracking-tight mb-20">
            <span class="text-[#002B49]">Our</span> 
            <span class="text-[#00E5A3]">Process</span>
        </h2>

        <div class="relative">
            
            <div class="hidden lg:block absolute top-0 left-0 w-full h-[220px] pointer-events-none z-0">
                <svg viewBox="0 0 1200 220" fill="none" xmlns="http://www.w3.org/2000/svg" class="w-full h-full">
                    <path d="M 150 64 
                             C 280 64, 320 128, 450 128 
                             C 580 128, 620 64, 750 64 
                             C 880 64, 920 128, 1025 128" 
                          stroke="url(#arrow-gradient-flow)" 
                          stroke-width="5" 
                          stroke-linecap="round"
                          class="animate-arrow-flow"/>
                    
                    <path d="M 1020 120 L 1035 128 L 1020 136 Z" fill="#00E5A3" />
                    
                    <defs>
                        <linearGradient id="arrow-gradient-flow" x1="0%" y1="0%" x2="100%" y2="0%">
                            <stop offset="0%" stop-color="#00C1FF"/>
                            <stop offset="33%" stop-color="#0066CC"/>
                            <stop offset="66%" stop-color="#0B2564"/>
                            <stop offset="100%" stop-color="#00E5A3"/>
                        </linearGradient>
                    </defs>
                </svg>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-12 lg:gap-0 relative z-10">
                
                <div class="flex flex-col items-center text-center space-y-5 group">
                    <div class="w-32 h-32 rounded-full bg-white flex items-center justify-center text-3xl text-[#1E1B4B] shadow-[inset_-12px_-12px_25px_rgba(0,0,0,0.12),0_20px_40px_rgba(0,0,0,0.18)] border border-gray-100/50 transition-transform duration-300 group-hover:scale-105">
                        <i class="fas fa-search"></i>
                    </div>
                    <div class="max-w-[200px] space-y-1">
                        <span class="text-xs font-black tracking-widest text-[#00C1FF] uppercase block">01. Discovery</span>
                        <p class="text-xs sm:text-sm text-gray-500 font-medium leading-relaxed">We learn about your business, workflows, and staffing requirements.</p>
                    </div>
                </div>

                <div class="flex flex-col items-center text-center space-y-5 group lg:pt-16">
                    <div class="w-32 h-32 rounded-full bg-white flex items-center justify-center text-3xl text-[#1E1B4B] shadow-[inset_-12px_-12px_25px_rgba(0,0,0,0.12),0_20px_40px_rgba(0,0,0,0.18)] border border-gray-100/50 transition-transform duration-300 group-hover:scale-105">
                        <i class="fas fa-user-check"></i>
                    </div>
                    <div class="max-w-[200px] space-y-1">
                        <span class="text-xs font-black tracking-widest text-[#0066CC] uppercase block">02. Talent Matching</span>
                        <p class="text-xs sm:text-sm text-gray-500 font-medium leading-relaxed">We identify professionals whose skills align with your needs.</p>
                    </div>
                </div>

                <div class="flex flex-col items-center text-center space-y-5 group">
                    <div class="w-32 h-32 rounded-full bg-white flex items-center justify-center text-3xl text-[#1E1B4B] shadow-[inset_-12px_-12px_25px_rgba(0,0,0,0.12),0_20px_40px_rgba(0,0,0,0.18)] border border-gray-100/50 transition-transform duration-300 group-hover:scale-105">
                        <i class="fas fa-laptop-house"></i>
                    </div>
                    <div class="max-w-[200px] space-y-1">
                        <span class="text-xs font-black tracking-widest text-[#0B2564] uppercase block">03. Onboarding</span>
                        <p class="text-xs sm:text-sm text-gray-500 font-medium leading-relaxed">Your offshore team is integrated into your systems and processes.</p>
                    </div>
                </div>

                <div class="flex flex-col items-center text-center space-y-5 group lg:pt-16">
                    <div class="w-32 h-32 rounded-full bg-white flex items-center justify-center text-3xl text-[#1E1B4B] shadow-[inset_-12px_-12px_25px_rgba(0,0,0,0.12),0_20px_40px_rgba(0,0,0,0.18)] border border-gray-100/50 transition-transform duration-300 group-hover:scale-105">
                        <i class="fas fa-chart-line"></i>
                    </div>
                    <div class="max-w-[200px] space-y-1">
                        <span class="text-xs font-black tracking-widest text-[#00E5A3] uppercase block">04. Ongoing Support</span>
                        <p class="text-xs sm:text-sm text-gray-500 font-medium leading-relaxed">We continuously monitor performance, provide administrative support, and help your team scale as your business grows.</p>
                    </div>
                </div>

            </div>
        </div>

    </div>
</section>

<!-- TESTIMONIAL BLOCK (Muted Sky Tint Layout) -->
<section class="bg-[#EDF4FF] py-20 px-8">
    <div class="max-w-4xl mx-auto text-center" data-reveal="up">
        <div class="text-[#1A1A1A]/40 text-5xl mb-6"><i class="fas fa-quote-left fa-solid"></i></div>
        <blockquote class="text-3xl font-black text-[#1A1A1A] italic leading-relaxed mb-6">
            "PhilPro quickly became an extension of our accounting team. Their professionalism, communication, and quality of work exceeded our expectations."
        </blockquote>
        <p class="text-xl font-black uppercase text-[#1A1A1A] tracking-wider">— Future Client Name</p>
    </div>
</section>

<!-- FINAL CALL TO ACTION (CTA) (Hero Banner Matching Visual Design) -->
<section class="relative bg-cover bg-center bg-no-repeat py-24 px-6 sm:px-12 lg:px-20 flex items-center bg-[#050B14] overflow-hidden" 
         style="background-image: url('https://images.unsplash.com/photo-1454165804606-c3d57bc86b40?q=80&w=1600&auto=format&fit=crop'); background-color: #050B14;">

    <!-- UPDATED: Brand-Aligned Deep Navy Overlay -->
<div class="absolute inset-0 bg-gradient-to-r from-[#001a4d]/95 via-[#002b80]/85 to-transparent z-10"></div>

    <div class="max-w-4xl mx-auto text-center relative z-10 space-y-8" data-reveal="up">
        
        <!-- Main Headline -->
        <h2 class="text-4xl font-black uppercase leading-tight tracking-tight text-white-force text-white"
            style="color: #FFFFFF !important; text-shadow: 0px 2px 4px rgba(0,0,0,0.4);">
            Ready to Build Your Offshore Accounting Team?
        </h2>
        
        <!-- Supporting Subparagraph -->
        <p class="text-xl sm:text-2xl max-w-2xl mx-auto leading-relaxed text-white-force text-gray-300"
           style="color: #E5E7EB !important; text-shadow: 0px 1px 2px rgba(0,0,0,0.4);">
            Partner with PhilPro to gain reliable accounting and tax outsourcing solutions backed by skilled Filipino professionals. Let's discuss how we can support your business.
        </p>
        
        <!-- Outlined Action Button Matching Hero Section -->
        <div class="pt-4">
            <a href="/contact" class="bg-transparent border-2 border-white text-base font-bold uppercase tracking-wider px-10 py-4 rounded hover:bg-[#CC0000] hover:border-[#CC0000] transition-colors duration-300 shadow-lg min-w-[180px] text-center inline-block no-underline"
               style="color: #FFFFFF !important; border-color: #FFFFFF !important;">
                Contact Us Today
            </a>
        </div>
        
    </div>
</section>