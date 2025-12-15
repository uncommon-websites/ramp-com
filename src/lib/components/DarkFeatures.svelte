<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="bg-ramp-dark text-white py-32">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-32">
            <h2 class="text-4xl md:text-6xl font-serif mb-6 tracking-tight leading-tight">Three ways we save your<br/>company both time and money.</h2>
            <p class="text-gray-400 mb-10 text-lg">There are many more, but we thought we'd ease you into it.</p>
            <a href="#" class="inline-flex items-center text-white font-medium hover:text-gray-300 transition-colors group">
                Learn more <ArrowRight size={16} class="ml-1 group-hover:translate-x-1 transition-transform" />
            </a>
        </div>

        <div class="space-y-40">
            <!-- Feature 1 -->
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div>
                    <h3 class="text-3xl md:text-4xl font-serif mb-6">Set policies that enforce themselves.</h3>
                    <p class="text-gray-400 mb-8 leading-relaxed text-lg">
                        Customize approved flows, pre-approve funds, issue cards with built-in controls and stop out-of-policy spending.
                    </p>
                    <a href="#" class="inline-flex items-center text-white text-sm font-medium hover:text-gray-300 transition-colors group">
                        Expense management <ArrowRight size={14} class="ml-1 group-hover:translate-x-1 transition-transform" />
                    </a>
                </div>
                <div class="relative rounded-2xl overflow-hidden bg-gray-900 aspect-[4/3] shadow-2xl border border-gray-800 group">
                    <!-- Image placeholder representing people working at night -->
                    <div class="absolute inset-0 bg-gradient-to-br from-gray-800 to-black opacity-80 z-0"></div>
                     <!-- Abstract representation of office at night -->
                    <div class="absolute inset-0 flex items-center justify-center">
                        <div class="w-full h-full relative">
                            <!-- Window light effect -->
                            <div class="absolute top-10 right-10 w-32 h-32 bg-blue-900/20 blur-3xl rounded-full"></div>
                            <!-- Silhouette of person working -->
                            <div class="absolute bottom-0 right-20 w-40 h-40 bg-gray-800 rounded-t-full opacity-50"></div>
                            <div class="absolute bottom-0 right-10 w-20 h-20 bg-blue-500/10 rounded-full blur-xl"></div>
                        </div>
                    </div>
                    
                    <!-- UI Overlay -->
                    <div class="absolute top-1/2 left-10 -translate-y-1/2 bg-white rounded-lg p-4 shadow-xl w-64 transform -rotate-2 z-10">
                         <div class="flex items-center gap-3 mb-3">
                             <div class="w-8 h-8 rounded-full bg-gray-100 flex items-center justify-center text-xs">👤</div>
                             <div>
                                 <div class="h-2 w-20 bg-gray-200 rounded mb-1"></div>
                                 <div class="h-2 w-12 bg-gray-100 rounded"></div>
                             </div>
                         </div>
                         <div class="h-20 bg-gray-50 rounded border border-gray-100 p-2">
                             <div class="h-2 w-full bg-gray-200 rounded mb-2"></div>
                             <div class="h-2 w-2/3 bg-gray-200 rounded"></div>
                         </div>
                    </div>
                </div>
            </div>

            <!-- Feature 2 -->
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                 <div class="order-2 lg:order-1 relative rounded-2xl overflow-hidden bg-[#f4f4f5] aspect-[4/3] shadow-2xl group border border-gray-800">
                    <!-- UI Mockup: "It's a good price" -->
                    <div class="absolute inset-0 flex items-center justify-center p-8">
                        <div class="bg-white p-6 rounded-xl shadow-lg border border-gray-200 w-full max-w-sm">
                            <div class="flex items-center gap-3 mb-6">
                                <div class="w-10 h-10 bg-green-100 rounded-full flex items-center justify-center text-green-600">
                                    <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round">
                                        <polyline points="20 6 9 17 4 12"></polyline>
                                    </svg>
                                </div>
                                <div>
                                    <div class="text-base font-bold text-gray-900">We've checked your quote.</div>
                                    <div class="text-xs text-green-700 font-bold bg-green-100 px-2 py-1 rounded inline-block mt-1">it's a good price</div>
                                </div>
                            </div>
                            
                            <div class="flex items-center gap-4 mb-4">
                                <div class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center text-gray-400 font-bold">S</div>
                                <div class="flex-1">
                                    <div class="h-2 bg-gray-200 w-full rounded mb-2"></div>
                                    <div class="h-2 bg-gray-100 w-1/2 rounded"></div>
                                </div>
                            </div>
                            
                            <div class="flex justify-between items-center mt-6 pt-4 border-t border-gray-100">
                                <div class="flex -space-x-2">
                                    <div class="w-6 h-6 rounded-full bg-gray-300 border-2 border-white"></div>
                                    <div class="w-6 h-6 rounded-full bg-gray-400 border-2 border-white"></div>
                                    <div class="w-6 h-6 rounded-full bg-gray-500 border-2 border-white"></div>
                                </div>
                                <div class="text-xs text-gray-400">00+ businesses sharing pricing data</div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="order-1 lg:order-2">
                    <h3 class="text-3xl md:text-4xl font-serif mb-6">Triple checks are done for you.</h3>
                    <p class="text-gray-400 mb-8 leading-relaxed text-lg">
                        Ramp keeps an eye out 24/7 to catch any out-of-policy transactions, uncover errors, and see where you're overspending.
                    </p>
                    <a href="#" class="inline-flex items-center text-white text-sm font-medium hover:text-gray-300 transition-colors group">
                        Intelligence <ArrowRight size={14} class="ml-1 group-hover:translate-x-1 transition-transform" />
                    </a>
                </div>
            </div>

            <!-- Feature 3 -->
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-20 items-center">
                <div>
                    <h3 class="text-3xl md:text-4xl font-serif mb-6">Leave the busywork to us.</h3>
                    <p class="text-gray-400 mb-8 leading-relaxed text-lg">
                        Keep everyone focused on the big picture, and let Ramp automate the rest—expenses, accounting, compliance, and more.
                    </p>
                    <a href="#" class="inline-flex items-center text-white text-sm font-medium hover:text-gray-300 transition-colors group">
                        Accounting automation <ArrowRight size={14} class="ml-1 group-hover:translate-x-1 transition-transform" />
                    </a>
                </div>
                <div class="relative rounded-2xl overflow-hidden bg-white aspect-[4/3] shadow-2xl border border-gray-700 group">
                     <div class="absolute inset-0 bg-[#f4f4f5] p-12 flex flex-col justify-center items-center">
                        <!-- Today List -->
                        <div class="bg-white rounded-xl shadow-lg border border-gray-200 overflow-hidden w-full max-w-md">
                            <div class="px-6 py-4 border-b border-gray-100 flex justify-between items-center">
                                <span class="font-bold text-xl text-gray-900">Today</span>
                                <span class="text-xs text-gray-500 bg-gray-100 px-2 py-1 rounded font-medium">May 12</span>
                            </div>
                            <div class="p-2">
                                <div class="flex items-center justify-between p-3 hover:bg-gray-50 rounded transition-colors cursor-pointer">
                                    <div class="flex items-center gap-4">
                                        <div class="w-10 h-10 bg-blue-50 rounded-lg flex items-center justify-center text-blue-500 text-lg">💧</div>
                                        <span class="text-base font-medium text-gray-900">Blue Bottle</span>
                                    </div>
                                    <span class="text-base font-medium text-gray-900">$11.83</span>
                                </div>
                                <div class="flex items-center justify-between p-3 bg-gray-50 rounded transition-colors cursor-pointer border border-gray-100 shadow-sm">
                                    <div class="flex items-center gap-4">
                                        <div class="w-10 h-10 bg-black rounded-lg flex items-center justify-center text-white text-lg">U</div>
                                        <span class="text-base font-medium text-gray-900">Uber</span>
                                    </div>
                                    <div class="flex items-center gap-2">
                                        <ArrowRight size={16} class="text-gray-400" />
                                    </div>
                                </div>
                                <div class="flex items-center justify-between p-3 hover:bg-gray-50 rounded transition-colors cursor-pointer">
                                    <div class="flex items-center gap-4">
                                        <div class="w-10 h-10 bg-green-50 rounded-lg flex items-center justify-center text-green-600 text-lg">🥗</div>
                                        <span class="text-base font-medium text-gray-900">Sweetgreen</span>
                                    </div>
                                    <span class="text-base font-medium text-gray-900">$27.50</span>
                                </div>
                            </div>
                        </div>
                     </div>
                </div>
            </div>
        </div>
    </div>
</section>
