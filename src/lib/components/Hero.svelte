<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="relative bg-ramp-dark text-white pt-32 pb-20 overflow-hidden">
    <!-- Background Gradient -->
    <div class="absolute top-0 left-0 w-full h-full bg-gradient-to-br from-ramp-dark via-[#0f1525] to-[#1a2333] z-0"></div>
    
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
            <!-- Left Content -->
            <div>
                <div class="flex items-center gap-2 mb-6">
                    <div class="w-5 h-5 rounded-full border border-white/20 flex items-center justify-center">
                        <span class="text-[10px] font-mono text-yellow-400">★</span>
                    </div>
                    <span class="text-sm text-gray-400 font-medium">5,000+ 5-star reviews</span>
                </div>
                
                <h1 class="text-5xl md:text-7xl font-serif leading-[1.1] mb-6 tracking-tight">
                    Time is money.<br/>Save both.
                </h1>
                
                <p class="text-xl text-gray-400 mb-8 max-w-lg leading-relaxed">
                    Easy-to-use corporate cards, bill payments, accounting, and a whole lot more. All in one place.
                </p>
                
                <div class="bg-white p-1 rounded-lg max-w-md flex items-center mb-6 shadow-lg">
                    <input 
                        type="email" 
                        placeholder="What's your work email?" 
                        class="flex-1 bg-transparent border-none outline-none px-4 text-gray-900 placeholder-gray-500 h-12"
                    />
                    <button class="bg-ramp-yellow text-ramp-dark px-6 h-12 rounded font-medium hover:bg-yellow-300 transition-colors whitespace-nowrap">
                        Get started for free
                    </button>
                </div>
                
                <a href="#" class="inline-flex items-center text-white font-medium hover:text-gray-300 transition-colors group">
                    Explore product <ArrowRight size={16} class="ml-1 group-hover:translate-x-1 transition-transform" />
                </a>
            </div>
            
            <!-- Right Content (Visuals) -->
            <div class="relative h-[500px] w-full hidden md:block">
                <!-- Monitor -->
                <div class="absolute top-10 right-0 w-[90%] h-[400px] bg-white rounded-lg shadow-2xl overflow-hidden border border-gray-700 z-10">
                    <div class="h-8 bg-gray-50 border-b border-gray-200 flex items-center px-4 gap-2">
                        <div class="w-3 h-3 rounded-full bg-red-400"></div>
                        <div class="w-3 h-3 rounded-full bg-yellow-400"></div>
                        <div class="w-3 h-3 rounded-full bg-green-400"></div>
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-end mb-8">
                            <div>
                                <div class="h-4 w-32 bg-gray-200 rounded mb-2"></div>
                                <div class="h-8 w-48 bg-gray-800 rounded"></div>
                            </div>
                            <div class="h-8 w-24 bg-gray-200 rounded"></div>
                        </div>
                        <!-- Chart placeholder -->
                        <div class="h-48 w-full bg-blue-50/50 rounded-lg flex items-end justify-between px-4 pb-4 gap-2">
                            {#each Array(15) as _, i}
                                <div class="w-full bg-blue-500/20 rounded-t" style="height: {30 + Math.random() * 60}%"></div>
                            {/each}
                        </div>
                    </div>
                </div>
                
                <!-- Phone -->
                <div class="absolute bottom-0 right-12 w-[200px] h-[350px] bg-black rounded-[30px] border-[8px] border-gray-800 shadow-2xl z-20 overflow-hidden">
                    <div class="absolute top-0 left-1/2 -translate-x-1/2 w-24 h-6 bg-gray-800 rounded-b-xl z-30"></div>
                    <div class="bg-white w-full h-full pt-12 px-4">
                        <div class="h-8 w-24 bg-gray-200 rounded mb-4"></div>
                        <div class="h-24 w-full bg-blue-50 rounded-lg mb-4 p-2">
                             <div class="h-full w-full bg-blue-100 rounded"></div>
                        </div>
                        <div class="space-y-2">
                            <div class="h-12 w-full bg-gray-50 rounded flex items-center px-2 gap-2">
                                <div class="w-8 h-8 rounded-full bg-gray-200"></div>
                                <div class="h-3 w-20 bg-gray-200 rounded"></div>
                            </div>
                            <div class="h-12 w-full bg-gray-50 rounded flex items-center px-2 gap-2">
                                <div class="w-8 h-8 rounded-full bg-gray-200"></div>
                                <div class="h-3 w-20 bg-gray-200 rounded"></div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Card -->
                <div class="absolute bottom-12 right-[180px] w-[240px] h-[150px] bg-gray-900 rounded-xl shadow-2xl z-30 flex flex-col justify-between p-4 border border-gray-700 transform -rotate-6 transition-transform hover:rotate-0">
                    <div class="flex justify-between items-start">
                        <div class="w-10 h-7 bg-yellow-600/50 rounded flex items-center justify-center">
                            <div class="w-6 h-4 border border-yellow-400 rounded-sm"></div>
                        </div> <!-- Chip -->
                        <div class="text-white font-bold italic tracking-widest">RAMP</div>
                    </div>
                    <div class="text-white/50 font-mono text-sm tracking-widest">•••• •••• •••• 4242</div>
                </div>
            </div>
        </div>
        
        <!-- Social Proof -->
        <div class="mt-20 border-t border-gray-800 pt-8">
            <p class="text-center text-gray-500 text-sm mb-8">50,000+ finance teams have saved millions of hours with Ramp.</p>
            <div class="flex flex-wrap justify-center items-center gap-x-12 gap-y-8 opacity-60">
                <!-- Logos (Placeholders - using text for simplicity but styled to look like logos) -->
                <span class="text-xl font-bold text-white font-sans tracking-tight">Discord</span>
                <span class="text-xl font-bold text-white font-serif italic">GoodRx</span>
                <span class="text-xl font-extrabold text-white tracking-widest uppercase font-sans">BARRY'S</span>
                <span class="text-xl font-medium text-white tracking-tight text-orange-400">eventbrite</span>
                <span class="text-xl font-bold text-white font-mono">ANGEL</span>
                <span class="text-xl font-bold text-white font-sans text-green-400">shopify</span>
                <span class="text-xl font-bold text-white font-sans tracking-tighter">Opendoor</span>
            </div>
        </div>
    </div>
</section>
