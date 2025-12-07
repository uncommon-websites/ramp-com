<script lang="ts">
  const products = [
    {
      title: "Ramp Intelligence",
      desc: "Put Ramp AI to work for you.",
      visual: "intelligence"
    },
    {
      title: "Corporate Cards",
      desc: "Control spend before it happens.",
      visual: "cards"
    },
    {
      title: "Expense Management",
      desc: "Expenses that submit themselves.",
      visual: "expense"
    },
    {
      title: "Accounts Payable",
      desc: "Process bills in seconds.",
      visual: "ap"
    },
    {
      title: "Travel",
      desc: "Travel that's always in policy.",
      visual: "travel"
    },
    {
      title: "Procurement",
      desc: "Run intake-to-pay without delay.",
      visual: "procurement"
    },
    {
      title: "Accounting Automation",
      desc: "Accelerate your monthly close.",
      visual: "accounting"
    },
    {
      title: "Ramp Treasury",
      desc: "Business accounts that earn more.",
      visual: "treasury"
    }
  ];
</script>

<section class="py-24 bg-white">
  <div class="max-w-7xl mx-auto px-6 md:px-8">
    <div class="mb-16">
      <h4 class="text-sm font-medium text-gray-500 mb-2">Ramp Product Suite</h4>
      <h2 class="text-4xl md:text-5xl font-medium tracking-tight mb-4">Get to know Ramp</h2>
      <p class="text-xl text-gray-500 max-w-2xl">
        Replace multiple broken tools with Ramp, the only platform designed to make your finance team faster—and happier.
      </p>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6">
      {#each products as product}
        <div class="bg-gray-50 rounded-2xl p-6 flex flex-col h-[400px] group hover:shadow-lg transition-shadow border border-transparent hover:border-gray-200 overflow-hidden relative">
          <h3 class="text-xl font-medium mb-2">{product.title}</h3>
          <p class="text-gray-500 text-sm mb-4">{product.desc}</p>
          <a href="#" class="text-sm font-medium flex items-center gap-1 mb-6 hover:underline">
            Learn more 
            <svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7" /></svg>
          </a>
          
          <!-- Visual Container -->
          <div class="flex-1 relative w-full">
            {#if product.visual === 'intelligence'}
              <div class="absolute inset-x-4 top-4 bottom-0 bg-white rounded-t-lg border border-gray-200 shadow-sm p-3">
                 <div class="h-2 w-1/3 bg-gray-100 rounded mb-3"></div>
                 <div class="space-y-2">
                    <div class="h-8 bg-blue-50 rounded w-full"></div>
                    <div class="h-8 bg-gray-50 rounded w-full"></div>
                 </div>
              </div>
            {:else if product.visual === 'cards'}
              <div class="absolute right-[-20px] bottom-[-40px] w-48 h-32 bg-gray-900 rounded-xl transform -rotate-12 shadow-xl border border-gray-700 p-3">
                  <div class="text-white/50 text-xs italic">ramp</div>
                  <div class="mt-8 h-6 w-10 bg-yellow-500/20 rounded"></div>
              </div>
              <div class="absolute right-[20px] bottom-[-40px] w-48 h-32 bg-black rounded-xl transform -rotate-6 shadow-2xl border border-gray-800 p-3">
                  <div class="text-white font-bold italic">ramp</div>
                  <div class="mt-8 flex justify-between items-end">
                      <div class="h-6 w-10 bg-yellow-500/20 rounded"></div>
                      <div class="text-white/80 text-xs">•••• 4242</div>
                  </div>
              </div>
            {:else if product.visual === 'expense'}
               <div class="absolute bottom-0 left-1/2 -translate-x-1/2 w-32 h-48 bg-black rounded-t-[2rem] border-x-[4px] border-t-[4px] border-gray-800 shadow-xl overflow-hidden">
                   <div class="w-full h-full bg-white p-2">
                       <div class="w-full h-24 bg-gray-100 rounded mb-2 flex items-center justify-center">
                           <svg class="w-8 h-8 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 9a2 2 0 012-2h.93a2 2 0 001.664-.89l.812-1.22A2 2 0 0110.07 4h3.86a2 2 0 011.664.89l.812 1.22A2 2 0 0018.07 7H19a2 2 0 012 2v9a2 2 0 01-2 2H5a2 2 0 01-2-2V9z" /><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 13a3 3 0 11-6 0 3 3 0 016 0z" /></svg>
                       </div>
                       <div class="h-2 w-16 bg-green-500 rounded mx-auto"></div>
                   </div>
               </div>
            {:else if product.visual === 'ap'}
               <div class="absolute inset-0 flex items-center justify-center">
                   <div class="relative">
                       <div class="w-20 h-24 bg-white border border-gray-200 shadow-sm rounded flex items-center justify-center rotate-[-10deg] absolute top-0 left-0">
                           <div class="w-8 h-1 bg-gray-200 rounded"></div>
                       </div>
                       <div class="w-20 h-24 bg-white border border-gray-200 shadow-sm rounded flex items-center justify-center rotate-[5deg] z-10 relative">
                           <div class="w-8 h-8 rounded-full bg-orange-100 flex items-center justify-center text-orange-500">
                               <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M7 16a4 4 0 01-.88-7.903A5 5 0 1115.9 6L16 6a5 5 0 011 9.9M15 13l-3-3m0 0l-3 3m3-3v12" /></svg>
                           </div>
                       </div>
                       <div class="w-24 h-8 bg-blue-600 text-white text-[10px] flex items-center justify-center rounded-full absolute -bottom-8 -right-4 shadow-lg z-20">
                           invoice_002.pdf
                       </div>
                   </div>
               </div>
            {:else if product.visual === 'travel'}
               <div class="absolute inset-0 bg-blue-50/50 p-4">
                   <div class="relative w-full h-full">
                       <!-- Map pins -->
                       <div class="absolute top-4 left-4 bg-white px-2 py-1 rounded shadow text-xs font-bold text-gray-800">$190</div>
                       <div class="absolute top-12 right-8 bg-white px-2 py-1 rounded shadow text-xs font-bold text-gray-800">$480</div>
                       <div class="absolute bottom-12 left-12 bg-blue-600 text-white px-2 py-1 rounded shadow text-xs font-bold">$200</div>
                       
                       <div class="absolute bottom-4 left-4 bg-white p-2 rounded shadow-lg flex gap-2 items-center w-32">
                           <div class="w-8 h-8 bg-gray-200 rounded"></div>
                           <div class="text-[8px] leading-tight">
                               <div class="font-bold">Central Park</div>
                               <div class="text-gray-500">Hotel</div>
                           </div>
                       </div>
                   </div>
               </div>
            {:else if product.visual === 'procurement'}
               <div class="absolute inset-x-4 inset-y-2 flex flex-col gap-2 text-[10px]">
                   <div class="bg-white p-2 rounded border border-gray-200 shadow-sm flex items-center gap-2">
                       <div class="w-4 h-4 bg-blue-100 rounded-full flex items-center justify-center text-blue-600">1</div>
                       <span>When bill is created</span>
                   </div>
                   <div class="h-4 border-l-2 border-gray-200 ml-4"></div>
                   <div class="bg-white p-2 rounded border border-gray-200 shadow-sm flex items-center gap-2">
                        <div class="w-4 h-4 bg-gray-100 rounded text-gray-500 flex items-center justify-center">?</div>
                        <span>Amount > $5,000</span>
                   </div>
                   <div class="h-4 border-l-2 border-gray-200 ml-4"></div>
                   <div class="flex gap-2">
                       <div class="bg-white px-2 py-1 rounded border border-gray-200 shadow-sm">Require Approval</div>
                   </div>
               </div>
            {:else if product.visual === 'accounting'}
               <div class="absolute inset-x-4 top-4 bg-white rounded-t-lg border border-gray-200 shadow-sm p-3">
                   <div class="text-xs font-bold mb-2">Card transactions</div>
                   <div class="space-y-2">
                       <div class="flex items-center justify-between text-[10px]">
                           <div class="flex items-center gap-1">
                               <div class="w-4 h-4 bg-black rounded-full"></div>
                               <span>Uber</span>
                           </div>
                           <span>-$24.00</span>
                       </div>
                       <div class="h-px bg-gray-100"></div>
                       <div class="flex items-center justify-between text-[10px]">
                           <div class="flex items-center gap-1">
                               <div class="w-4 h-4 bg-blue-500 rounded-full"></div>
                               <span>Software</span>
                           </div>
                           <span>-$120.00</span>
                       </div>
                   </div>
               </div>
            {:else if product.visual === 'treasury'}
               <div class="absolute inset-0 p-4 flex items-end">
                   <div class="w-full h-32 relative">
                       <svg class="w-full h-full overflow-visible" preserveAspectRatio="none">
                           <path d="M0 100 C 50 100, 50 20, 100 20 S 150 60, 200 10" fill="none" stroke="#3b82f6" stroke-width="2" />
                           <path d="M0 100 C 50 100, 50 20, 100 20 S 150 60, 200 10 V 120 H 0 Z" fill="url(#gradient)" opacity="0.1" />
                           <defs>
                               <linearGradient id="gradient" x1="0" y1="0" x2="0" y2="1">
                                   <stop offset="0%" stop-color="#3b82f6" />
                                   <stop offset="100%" stop-color="white" />
                               </linearGradient>
                           </defs>
                       </svg>
                       <div class="absolute top-0 right-0 text-right">
                           <div class="text-xs text-gray-500">Investment account</div>
                           <div class="text-lg font-bold text-blue-600">3.97%</div>
                       </div>
                   </div>
               </div>
            {/if}
          </div>
        </div>
      {/each}
    </div>
  </div>
</section>
