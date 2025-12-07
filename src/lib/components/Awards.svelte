<section class="py-24 bg-white border-t border-gray-100">
  <div class="max-w-7xl mx-auto px-6 md:px-8 text-center">
    <div class="flex flex-col items-center mb-12">
      <div class="w-12 h-12 bg-red-500 rounded-lg flex items-center justify-center text-white font-bold text-xl mb-4">G</div>
      <div class="font-medium text-lg">5 star rating</div>
      <div class="text-gray-500 text-sm">2,000+ reviews</div>
    </div>

    <div class="flex flex-wrap justify-center gap-8 md:gap-12 opacity-80">
      {#each Array(6) as _, i}
        <div class="w-24 h-32 bg-gray-50 border border-gray-200 rounded p-2 flex flex-col items-center justify-center gap-2">
            <div class="w-12 h-12 bg-red-100 rounded-full flex items-center justify-center text-red-600 font-bold text-xs">G2</div>
            <div class="text-[10px] text-center font-medium text-gray-600">Leader<br>Winter 2024</div>
        </div>
      {/each}
    </div>
  </div>
</section>
