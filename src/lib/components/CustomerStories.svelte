<script>
    import { ArrowRight, Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
            <h2 class="text-4xl md:text-5xl font-serif mb-4 text-gray-900 tracking-tight">What would you do with more time?</h2>
            <p class="text-gray-500 mb-6 text-lg">Over 200m+ hours saved for 50,000+ customers.</p>
            <a href="#" class="inline-flex items-center text-gray-900 font-medium hover:opacity-70 transition-opacity">
                View all customer stories <ArrowRight size={16} class="ml-1" />
            </a>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            <!-- Card 1 -->
            <div class="relative aspect-[3/4] rounded-xl overflow-hidden group cursor-pointer bg-gray-100">
                <div class="absolute inset-0 bg-gray-200 flex items-center justify-center">
                    <span class="text-6xl opacity-10">👤</span>
                </div> 
                <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
                <div class="absolute top-6 left-6">
                    <span class="text-white font-bold text-xl tracking-widest">STEDI</span>
                </div>
                <div class="absolute bottom-6 left-6 bg-white/20 backdrop-blur-md w-10 h-10 flex items-center justify-center rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                    <Play size={16} class="text-white fill-current ml-0.5" />
                </div>
            </div>

            <!-- Card 2 -->
            <div class="relative aspect-[3/4] rounded-xl overflow-hidden group cursor-pointer bg-gray-100">
                <div class="absolute inset-0 bg-gray-300 flex items-center justify-center">
                    <span class="text-6xl opacity-10">👥</span>
                </div>
                <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
                <div class="absolute top-6 left-6">
                    <span class="text-white font-bold text-xl tracking-tighter flex items-center gap-1">
                        <span class="text-2xl">≫</span> MARQETA
                    </span>
                </div>
                <div class="absolute bottom-6 left-6 bg-white/20 backdrop-blur-md w-10 h-10 flex items-center justify-center rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                    <Play size={16} class="text-white fill-current ml-0.5" />
                </div>
            </div>

            <!-- Card 3 -->
            <div class="relative aspect-[3/4] rounded-xl overflow-hidden group cursor-pointer bg-gray-100">
                <div class="absolute inset-0 bg-gray-400 flex items-center justify-center">
                    <span class="text-6xl opacity-10">🏢</span>
                </div>
                <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
                <div class="absolute top-6 left-6">
                    <span class="text-white font-bold text-xl font-serif italic">BVC</span>
                </div>
                <div class="absolute bottom-6 left-6 bg-white/20 backdrop-blur-md w-10 h-10 flex items-center justify-center rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                    <Play size={16} class="text-white fill-current ml-0.5" />
                </div>
            </div>

            <!-- Card 4 -->
            <div class="relative aspect-[3/4] rounded-xl overflow-hidden group cursor-pointer bg-gray-100">
                <div class="absolute inset-0 bg-gray-500 flex items-center justify-center">
                    <span class="text-6xl opacity-10">🏭</span>
                </div>
                <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
                <div class="absolute top-6 left-6">
                    <span class="text-white font-bold text-xl">Walther</span>
                </div>
                <div class="absolute bottom-6 left-6 bg-white/20 backdrop-blur-md w-10 h-10 flex items-center justify-center rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">
                    <Play size={16} class="text-white fill-current ml-0.5" />
                </div>
            </div>
        </div>
    </div>
</section>
