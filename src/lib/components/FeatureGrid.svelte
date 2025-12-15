<script>
    import { ArrowRight } from 'lucide-svelte';
    
    const features = [
        { title: "Ramp Intelligence", desc: "Put Ramp AI to work for you.", type: "ai" },
        { title: "Corporate Cards", desc: "Control spend before it happens.", type: "cards" },
        { title: "Expense Management", desc: "Expenses that submit themselves.", type: "expense" },
        { title: "Accounts Payable", desc: "Process bills in seconds.", type: "ap" },
        { title: "Travel", desc: "Travel that's always in policy.", type: "travel" },
        { title: "Procurement", desc: "Run intake-to-pay without delay.", type: "procurement" },
        { title: "Accounting Automation", desc: "Accelerate your monthly close.", type: "accounting" },
        { title: "Ramp Treasury", desc: "Business accounts that earn more.", type: "treasury" }
    ];
</script>

<section class="py-24 bg-white">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif mb-4 text-gray-900 tracking-tight">Get to know Ramp</h2>
            <p class="text-xl text-gray-500 max-w-2xl leading-relaxed">
                Replace multiple broken tools with Ramp, the only platform designed to make your finance team faster—and happier.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
            {#each features as feature}
                <div class="bg-ramp-card rounded-xl p-6 hover:shadow-lg transition-shadow duration-300 group flex flex-col h-[340px]">
                    <div class="mb-6">
                        <h3 class="text-lg font-semibold text-gray-900 mb-1">{feature.title}</h3>
                        <p class="text-sm text-gray-500 mb-3">{feature.desc}</p>
                        <a href="#" class="inline-flex items-center text-sm font-medium text-gray-900 group-hover:opacity-70 transition-opacity">
                            Learn more <ArrowRight size={14} class="ml-1" />
                        </a>
                    </div>
                    
                    <div class="flex-1 bg-white rounded-lg border border-gray-100 overflow-hidden relative shadow-sm">
                        <!-- Visuals based on type -->
                        {#if feature.type === 'ai'}
                            <div class="p-4 space-y-3">
                                <div class="h-2 w-1/2 bg-gray-100 rounded"></div>
                                <div class="h-2 w-3/4 bg-gray-100 rounded"></div>
                                <div class="mt-4 p-3 bg-blue-50/50 rounded border border-blue-100">
                                    <div class="flex gap-2 mb-2">
                                        <div class="w-2 h-2 rounded-full bg-blue-400"></div>
                                        <div class="h-2 w-20 bg-blue-200 rounded"></div>
                                    </div>
                                    <div class="h-2 w-full bg-blue-100 rounded mb-1"></div>
                                    <div class="h-2 w-2/3 bg-blue-100 rounded"></div>
                                </div>
                            </div>
                        {:else if feature.type === 'cards'}
                            <div class="relative h-full w-full flex items-center justify-center overflow-hidden">
                                <div class="w-32 h-20 bg-black rounded-lg shadow-lg transform -rotate-12 absolute top-10 left-2 border border-gray-700 flex items-end p-2">
                                    <div class="text-[6px] text-white">VISA</div>
                                </div>
                                <div class="w-32 h-20 bg-gray-800 rounded-lg shadow-lg transform rotate-6 absolute top-12 left-8 border border-gray-600 flex items-end p-2">
                                    <div class="text-[6px] text-white">VISA</div>
                                </div>
                            </div>
                        {:else if feature.type === 'expense'}
                            <div class="p-4 flex flex-col items-center justify-center h-full">
                                <div class="w-20 h-24 bg-white border border-gray-200 shadow-sm p-2 text-[6px] text-gray-400 transform rotate-3">
                                    <div class="flex justify-between mb-2"><span>Uber</span><span>$12.00</span></div>
                                    <div class="h-1 w-full bg-gray-100 mt-1"></div>
                                    <div class="h-1 w-full bg-gray-100 mt-1"></div>
                                    <div class="h-1 w-1/2 bg-gray-100 mt-1"></div>
                                </div>
                                <div class="mt-[-10px] z-10 text-[10px] text-green-700 font-medium bg-green-100 px-2 py-0.5 rounded-full border border-green-200 shadow-sm">Matched</div>
                            </div>
                        {:else if feature.type === 'ap'}
                            <div class="p-4 relative h-full flex items-center justify-center">
                                <div class="w-10 h-10 rounded-full bg-gray-50 border border-gray-200 flex items-center justify-center text-lg absolute left-8 top-8 z-0">📄</div>
                                <div class="w-16 h-0.5 bg-gray-200 absolute left-12 top-12 z-0"></div>
                                <div class="w-10 h-10 rounded-full bg-blue-50 border border-blue-100 flex items-center justify-center text-blue-500 text-lg absolute right-8 top-12 z-10 shadow-sm">✓</div>
                            </div>
                        {:else if feature.type === 'travel'}
                            <div class="p-5">
                                <div class="flex justify-between text-[10px] font-bold text-gray-500 mb-3 tracking-widest">
                                    <span>SFO</span>
                                    <span class="text-gray-300">✈️</span>
                                    <span>JFK</span>
                                </div>
                                <div class="h-1.5 w-full bg-gray-100 rounded-full overflow-hidden mb-4">
                                    <div class="h-full w-2/3 bg-blue-500 rounded-full"></div>
                                </div>
                                <div class="flex gap-2">
                                    <div class="w-8 h-8 rounded bg-gray-50 border border-gray-100 flex items-center justify-center text-xs">🏨</div>
                                    <div class="w-8 h-8 rounded bg-gray-50 border border-gray-100 flex items-center justify-center text-xs">🚗</div>
                                </div>
                            </div>
                        {:else if feature.type === 'procurement'}
                            <div class="p-5 space-y-3">
                                <div class="flex items-center gap-3">
                                    <div class="w-5 h-5 rounded-full border border-gray-200 flex items-center justify-center text-[8px] text-gray-400">1</div>
                                    <div class="h-2 w-24 bg-gray-100 rounded"></div>
                                </div>
                                <div class="flex items-center gap-3">
                                    <div class="w-5 h-5 rounded-full border border-green-200 bg-green-50 flex items-center justify-center text-[8px] text-green-600">✓</div>
                                    <div class="h-2 w-24 bg-gray-100 rounded"></div>
                                </div>
                                <div class="flex items-center gap-3 opacity-50">
                                    <div class="w-5 h-5 rounded-full border border-gray-200 flex items-center justify-center text-[8px] text-gray-400">3</div>
                                    <div class="h-2 w-24 bg-gray-100 rounded"></div>
                                </div>
                            </div>
                        {:else if feature.type === 'accounting'}
                            <div class="p-4 grid grid-cols-2 gap-3">
                                <div class="h-10 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-[10px] text-gray-400">QBO</div>
                                <div class="h-10 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-[10px] text-gray-400">Xero</div>
                                <div class="h-10 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-[10px] text-gray-400">Sage</div>
                                <div class="h-10 bg-gray-50 rounded border border-gray-100 flex items-center justify-center text-[10px] text-gray-400">NetS</div>
                            </div>
                        {:else if feature.type === 'treasury'}
                            <div class="p-4 flex items-end h-full pb-0 gap-2 px-6">
                                <div class="w-1/4 h-[40%] bg-blue-100 rounded-t"></div>
                                <div class="w-1/4 h-[60%] bg-blue-200 rounded-t"></div>
                                <div class="w-1/4 h-[50%] bg-blue-300 rounded-t"></div>
                                <div class="w-1/4 h-[80%] bg-blue-400 rounded-t"></div>
                            </div>
                        {/if}
                    </div>
                </div>
            {/each}
        </div>
    </div>
</section>
