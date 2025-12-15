<script>
    import { Play } from 'lucide-svelte';
</script>

<section class="py-24 bg-white overflow-hidden">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <h2 class="text-4xl md:text-5xl font-serif mb-16 text-gray-900 text-center md:text-left tracking-tight">Don't just take our word for it.</h2>
        
        <div class="relative">
            <!-- Main Card -->
            <div class="flex flex-col md:flex-row gap-12 items-center">
                <!-- Video Thumbnail -->
                <div class="w-full md:w-[65%] relative rounded-2xl overflow-hidden shadow-2xl aspect-video bg-gray-900 group cursor-pointer">
                    <!-- Placeholder Image - simulating the man in the screenshot -->
                    <div class="absolute inset-0 bg-gradient-to-t from-black/50 to-transparent z-10"></div>
                    <div class="absolute inset-0 bg-gray-700 flex items-center justify-center">
                         <!-- Simple SVG Face Placeholder -->
                         <svg viewBox="0 0 100 100" class="w-full h-full text-gray-600 fill-current opacity-50">
                            <rect width="100" height="100" fill="#334155"/>
                            <circle cx="50" cy="40" r="15" fill="#475569"/>
                            <path d="M20 90 Q50 50 80 90" fill="#475569"/>
                         </svg>
                    </div>
                    
                    <!-- Notion Logo -->
                    <div class="absolute top-8 left-8 bg-white/20 backdrop-blur-md px-4 py-2 rounded-lg flex items-center gap-2 z-20">
                        <div class="w-5 h-5 bg-white rounded-sm flex items-center justify-center text-[10px] font-bold text-black">N</div>
                        <span class="text-white font-medium text-base">Notion</span>
                    </div>
                    
                    <!-- Play Button -->
                    <div class="absolute bottom-8 left-8 w-12 h-12 bg-ramp-yellow rounded-full flex items-center justify-center text-ramp-dark transition-transform group-hover:scale-110 z-20 shadow-lg cursor-pointer">
                        <Play size={20} fill="currentColor" class="ml-1" />
                    </div>
                </div>
                
                <!-- Quote Content -->
                <div class="w-full md:w-[35%] flex flex-col justify-center h-full py-4">
                    <div>
                        <blockquote class="text-2xl md:text-3xl font-medium leading-tight text-gray-900 mb-8 font-sans">
                            "Ramp is the only vendor that can service all of our employees across the globe in one unified system."
                        </blockquote>
                        <div class="mb-10">
                            <div class="font-bold text-gray-900 text-lg">Brandon Zatt</div>
                            <div class="text-gray-500 text-base">Chief Accounting Officer</div>
                        </div>
                    </div>
                    
                    <button class="bg-black text-white px-8 py-4 rounded-lg font-medium hover:bg-gray-800 transition-colors self-start text-sm">
                        Read customer story
                    </button>
                </div>
            </div>
            
            <!-- Hint of other cards (carousel effect) -->
            <div class="hidden lg:block absolute top-0 -right-[20%] w-[300px] h-full opacity-40 pointer-events-none">
                 <div class="w-full aspect-video bg-gray-200 rounded-2xl mb-4 shadow-lg relative overflow-hidden">
                    <div class="absolute top-6 left-6 bg-white/80 px-3 py-1 rounded flex items-center gap-2">
                        <span class="text-xs font-bold">University</span>
                    </div>
                    <div class="absolute bottom-6 left-6 w-8 h-8 bg-ramp-yellow rounded-full flex items-center justify-center">
                        <Play size={12} fill="currentColor" />
                    </div>
                 </div>
            </div>
        </div>
    </div>
</section>
