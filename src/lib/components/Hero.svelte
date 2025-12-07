<script lang="ts">
</script>

<section class="relative bg-ramp-dark text-white pt-32 pb-20 overflow-hidden">
  <!-- Background Glow -->
  <div class="absolute top-0 left-1/2 -translate-x-1/2 w-[1000px] h-[600px] bg-blue-900/20 blur-[120px] rounded-full pointer-events-none"></div>

  <div class="max-w-7xl mx-auto px-6 md:px-8 relative z-10 grid lg:grid-cols-2 gap-12 items-center">
    <div class="max-w-xl">
      <!-- Star Rating -->
      <div class="flex items-center gap-2 mb-6 text-sm font-medium text-gray-300">
        <div class="bg-white/10 p-1 rounded-full">
           <svg class="w-4 h-4 text-white" fill="currentColor" viewBox="0 0 20 20">
             <path d="M9.049 2.927c.3-.921 1.603-.921 1.902 0l1.07 3.292a1 1 0 00.95.69h3.462c.969 0 1.371 1.24.588 1.81l-2.8 2.034a1 1 0 00-.364 1.118l1.07 3.292c.3.921-.755 1.688-1.54 1.118l-2.8-2.034a1 1 0 00-1.175 0l-2.8 2.034c-.784.57-1.838-.197-1.539-1.118l1.07-3.292a1 1 0 00-.364-1.118L2.98 8.72c-.783-.57-.38-1.81.588-1.81h3.461a1 1 0 00.951-.69l1.07-3.292z" />
           </svg>
        </div>
        <span>2,000+</span>
        <span class="text-gray-400">5 star reviews</span>
      </div>

      <h1 class="text-5xl md:text-7xl font-medium tracking-tight leading-[1.1] mb-6">
        Time is money.<br />
        Save both.
      </h1>

      <p class="text-xl text-gray-400 mb-8 leading-relaxed max-w-lg">
        Easy-to-use corporate cards, bill payments, accounting, and a whole lot more. All in one place.
      </p>

      <form class="flex flex-col sm:flex-row gap-2 max-w-md mb-6">
        <input 
          type="email" 
          placeholder="What's your work email?" 
          class="flex-1 px-4 py-3 rounded-md text-black focus:outline-none focus:ring-2 focus:ring-ramp-green"
        />
        <button type="submit" class="bg-ramp-green text-black px-6 py-3 rounded-md font-semibold hover:bg-[#c3e83f] transition-colors whitespace-nowrap">
          Get started for free
        </button>
      </form>

      <a href="#" class="inline-flex items-center text-gray-300 hover:text-white transition-colors gap-1 text-sm font-medium">
        Explore product 
        <svg class="w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
          <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3" />
        </svg>
      </a>
    </div>

    <div class="relative">
      <!-- Placeholder for the complex hero image -->
      <!-- We will build a CSS representation of the monitor/card/phone -->
      <div class="relative w-full aspect-[4/3]">
        <!-- Monitor -->
        <div class="absolute top-0 right-0 w-[90%] h-[80%] bg-gray-900 rounded-xl border border-gray-700 shadow-2xl overflow-hidden z-10">
            <!-- Header -->
            <div class="h-8 bg-gray-800 border-b border-gray-700 flex items-center px-3 gap-1">
                <div class="w-2 h-2 rounded-full bg-red-500"></div>
                <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
                <div class="w-2 h-2 rounded-full bg-green-500"></div>
            </div>
            <!-- Content -->
            <div class="p-4 bg-white h-full">
                <div class="flex justify-between items-center mb-4">
                    <div class="h-4 w-24 bg-gray-200 rounded"></div>
                    <div class="h-8 w-24 bg-gray-100 rounded"></div>
                </div>
                <div class="grid grid-cols-3 gap-4 mb-6">
                    <div class="h-24 bg-gray-50 rounded border border-gray-100"></div>
                    <div class="h-24 bg-gray-50 rounded border border-gray-100"></div>
                    <div class="h-24 bg-gray-50 rounded border border-gray-100"></div>
                </div>
                <div class="h-32 bg-gray-50 rounded border border-gray-100"></div>
            </div>
        </div>

        <!-- Phone -->
        <div class="absolute bottom-0 right-[10%] w-[25%] h-[60%] bg-black rounded-[2rem] border-[4px] border-gray-800 shadow-2xl z-20 overflow-hidden">
            <div class="w-full h-full bg-white relative">
                 <div class="absolute top-0 left-1/2 -translate-x-1/2 w-1/2 h-4 bg-black rounded-b-xl"></div>
                 <div class="mt-8 px-2 space-y-2">
                     <div class="h-8 w-full bg-gray-100 rounded"></div>
                     <div class="h-20 w-full bg-green-50 rounded border border-green-100"></div>
                     <div class="h-12 w-full bg-gray-50 rounded"></div>
                 </div>
            </div>
        </div>

        <!-- Card -->
        <div class="absolute bottom-[10%] right-[30%] w-[40%] aspect-[1.586] bg-gradient-to-br from-gray-800 to-black rounded-xl border border-gray-700 shadow-2xl z-30 flex flex-col justify-between p-4 transform -rotate-6">
             <div class="text-white font-bold italic">ramp</div>
             <div class="flex justify-between items-end">
                 <div class="w-8 h-5 bg-yellow-500/20 rounded"></div>
                 <div class="text-white text-xs tracking-widest">•••• 4242</div>
             </div>
        </div>
      </div>
    </div>
  </div>
</section>
