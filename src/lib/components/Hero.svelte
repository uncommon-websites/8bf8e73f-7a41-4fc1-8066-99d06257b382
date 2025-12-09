<script>
    // Hero Section
</script>

<section class="relative min-h-screen w-full flex flex-col justify-center pt-32 pb-20 overflow-hidden bg-white">
    
    <!-- Background Visual (Blurred Head Simulation) -->
    <div class="absolute inset-0 pointer-events-none z-0 flex items-center justify-center translate-x-1/4">
        <!-- Abstract Head Shape Simulation -->
        <div class="relative w-[600px] h-[700px]">
            <div class="absolute inset-0 bg-gradient-to-br from-gray-800 via-gray-400 to-transparent rounded-[40%_60%_70%_30%/50%_60%_30%_60%] blur-3xl opacity-20"></div>
            <div class="absolute top-20 left-20 w-80 h-80 bg-black rounded-full blur-[60px] opacity-10"></div>
        </div>
    </div>

    <!-- Content -->
    <div class="container relative z-10 grid grid-cols-12 h-full">
        <div class="col-span-12 md:col-span-5 flex flex-col justify-center h-full pt-10">
            <h2 class="text-base font-bold text-gray-900 mb-4">augen</h2>
            <h1 class="text-6xl md:text-[5.5rem] leading-[1.1] font-normal tracking-tight text-gray-900 mb-10">
                Beyond Humanware.
            </h1>
            
            <div class="flex flex-wrap items-center gap-3">
                <span class="text-sm text-gray-500 mr-2">Explore</span>
                <button class="px-5 py-2 rounded-full border border-[--color-brand-blue] text-[--color-brand-blue] text-xs font-medium hover:bg-blue-50 transition-colors">
                    A¹ Sense
                </button>
                <button class="px-5 py-2 rounded-full border border-[--color-brand-blue] text-[--color-brand-blue] text-xs font-medium hover:bg-blue-50 transition-colors">
                    B¹ Eye
                </button>
                <button class="px-5 py-2 rounded-full border border-[--color-brand-blue] text-[--color-brand-blue] text-xs font-medium hover:bg-blue-50 transition-colors">
                    A¹ Neuro
                </button>
            </div>
        </div>
    </div>

    <!-- Scroll Indicator -->
    <div class="absolute bottom-12 left-8 md:left-[calc((100vw-1280px)/2+1.5rem)]">
        <div class="w-10 h-10 border border-gray-200 rounded-full flex items-center justify-center text-gray-400">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path d="M12 4V20M12 20L18 14M12 20L6 14" stroke="currentColor" stroke-width="1.5" stroke-linecap="round" stroke-linejoin="round"/>
            </svg>
        </div>
    </div>
</section>
