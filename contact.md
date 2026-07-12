---
layout: page
title: Contact Us | PhilPro Global
---
<!-- Compact Contact Hero Banner -->
<section class="relative py-16 flex items-center overflow-hidden font-sans" 
         style="background-image: url('https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?q=80&w=2000'); background-size: cover; background-position: center;">

    <!-- Gradient Overlay: Deep Navy (Left) to Lighter Blue/Transparent (Right) -->
    <div class="absolute inset-0 z-10" 
         style="background: linear-gradient(90deg, rgba(0, 26, 77, 0.95) 0%, rgba(0, 51, 153, 0.7) 60%, rgba(0, 51, 153, 0.3) 100%);">
    </div>
    
    <div class="relative z-20 max-w-7xl mx-auto w-full px-8">
        <h1 class="text-4xl lg:text-5xl font-black uppercase tracking-widest text-white mb-2">Contact Us</h1>
        <p class="text-sm uppercase tracking-[0.2em] opacity-90 font-medium text-white">Let’s discuss how we can scale your finance team</p>
    </div>
</section>

<!-- Contact Content -->
<section class="py-16 px-8 bg-white font-sans">
    <div class="max-w-7xl mx-auto grid grid-cols-1 lg:grid-cols-3 gap-12">

        <!-- Sidebar -->
        <div class="lg:col-span-1 space-y-8">
            <div class="bg-[#F4F6F9] p-8">
                <h3 class="text-xl font-bold text-[#003399] uppercase mb-6 tracking-wide">Our Location</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Legazpi City, Albay<br>Bicol Region, Philippines</p>
                <div class="mt-8 space-y-4">
                    <p class="font-bold text-[#003399] text-xs uppercase tracking-widest">Email</p>
                    <p class="text-sm text-gray-700">hello@philpro.com</p>
                    <p class="font-bold text-[#003399] text-xs uppercase tracking-widest mt-6">Phone</p>
                    <p class="text-sm text-gray-700">+63 9XX XXX XXXX</p>
                </div>
            </div>
        </div>

      <!-- Form Area -->
<!-- Form Area -->
        <div class="lg:col-span-2">
            <h2 class="text-2xl font-black text-[#1A1A1A] uppercase mb-8 tracking-tight">Send Us A Message</h2>
            <form id="philproForm" class="grid grid-cols-1 md:grid-cols-2 gap-4">
                <input type="text" name="entry.2086976944" placeholder="First Name" required class="p-3 border border-gray-200 w-full outline-none focus:border-[#003399]">
                <input type="text" name="entry.557839567" placeholder="Last Name" required class="p-3 border border-gray-200 w-full outline-none focus:border-[#003399]">
                <input type="email" name="entry.1388243374" placeholder="Business Email" required class="col-span-2 p-3 border border-gray-200 w-full outline-none focus:border-[#003399]">
                <input type="tel" name="entry.1255012078" placeholder="Contact Number" required class="col-span-2 p-3 border border-gray-200 w-full outline-none focus:border-[#003399]">
        
                <!-- Subject Input -->
                <input type="text" name="entry.154717761" placeholder="Subject" required class="col-span-2 p-3 border border-gray-200 w-full outline-none focus:border-[#003399]">
                
                <textarea name="entry.1050020768" rows="4" placeholder="Your Message" required class="col-span-2 p-3 border border-gray-200 w-full outline-none focus:border-[#003399]"></textarea>
                
                <button type="submit" class="col-span-2 bg-[#003399] text-white py-4 font-bold uppercase tracking-widest hover:bg-[#002266] transition">Submit Inquiry</button>
            </form>
        
            <!-- Updated Success Message with Button -->
            <div id="successMsg" class="hidden mt-4 p-8 bg-green-100 border-2 border-green-200 rounded text-center">
                <p class="text-green-800 font-bold mb-6">Thank you! Your message has been sent.</p>
                <button id="resetFormBtn" class="bg-[#003399] text-white px-8 py-3 font-bold uppercase tracking-widest hover:bg-[#002266] transition">
                    Submit Another Inquiry
                </button>
            </div>
        </div>
        
        <script>
            const form = document.getElementById('philproForm');
            const successMsg = document.getElementById('successMsg');
            const resetFormBtn = document.getElementById('resetFormBtn');
        
            form.addEventListener('submit', function(e) {
                e.preventDefault();
                const data = new FormData(form);
                
                fetch("https://docs.google.com/forms/d/e/1FAIpQLSct9KsYK81oGDd5tQ_C2MDoBJGKnk1ncGJAU6I4oxaHPvGGCQ/formResponse", {
                    method: "POST",
                    body: data,
                    mode: "no-cors"
                }).then(() => {
                    form.reset();
                    form.style.display = 'none';
                    successMsg.classList.remove('hidden');
                });
            });
        
            // Reset visibility when clicking the new button
            resetFormBtn.addEventListener('click', function() {
                successMsg.classList.add('hidden');
                form.style.display = 'grid';
            });
        </script>
    </div>
</section>
<section class="py-20 bg-[#F4F6F9] px-8">
    <div class="max-w-5xl mx-auto text-center">
        <h2 class="text-3xl font-black text-[#003399] uppercase mb-12">Client Testimonials</h2>
        <div class="grid md:grid-cols-2 gap-8">
            <blockquote class="bg-white p-8 rounded shadow-sm italic text-gray-700">
                "PhilPro transformed our accounting efficiency. The integration was seamless."
                <footer class="mt-4 font-bold text-[#003399] not-italic">— CFO, Global Tech Firm</footer>
            </blockquote>
            <blockquote class="bg-white p-8 rounded shadow-sm italic text-gray-700">
                "The most reliable offshore partner we have ever worked with."
                <footer class="mt-4 font-bold text-[#003399] not-italic">— Director, Accounting Services</footer>
            </blockquote>
        </div>
    </div>
</section>