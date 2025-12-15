<script>
  import { Menu, X } from 'lucide-svelte';
  let isOpen = false;
</script>

<nav class="fixed top-0 left-0 right-0 z-50 bg-ramp-dark text-white border-b border-gray-800">
  <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
    <div class="flex items-center justify-between h-16">
      <!-- Logo -->
      <div class="flex-shrink-0 flex items-center gap-2">
        <svg viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="h-6 w-auto text-white">
            <path d="M4.5 19.5L19.5 4.5H4.5V19.5Z" fill="currentColor"/>
        </svg>
        <span class="font-bold text-xl tracking-tight">Ramp</span>
      </div>

      <!-- Desktop Menu -->
      <div class="hidden md:flex items-center space-x-8 text-sm font-medium">
        <a href="#" class="hover:text-gray-300 transition-colors">Products</a>
        <a href="#" class="hover:text-gray-300 transition-colors">Solutions</a>
        <a href="#" class="hover:text-gray-300 transition-colors">Customers</a>
        <a href="#" class="hover:text-gray-300 transition-colors">Resources</a>
        <a href="#" class="hover:text-gray-300 transition-colors">Pricing</a>
        <a href="#" class="hover:text-gray-300 transition-colors">Careers</a>
      </div>

      <!-- CTA Buttons -->
      <div class="hidden md:flex items-center space-x-4">
        <a href="#" class="text-sm font-medium hover:text-gray-300 transition-colors">Sign in</a>
        <a href="#" class="bg-ramp-yellow text-ramp-dark px-4 py-2 rounded text-sm font-medium hover:bg-yellow-300 transition-colors">
          See a demo
        </a>
      </div>

      <!-- Mobile menu button -->
      <div class="md:hidden flex items-center">
        <button on:click={() => isOpen = !isOpen} class="text-gray-300 hover:text-white focus:outline-none">
          {#if isOpen}
            <X size={24} />
          {:else}
            <Menu size={24} />
          {/if}
        </button>
      </div>
    </div>
  </div>

  <!-- Mobile Menu -->
  {#if isOpen}
    <div class="md:hidden bg-ramp-dark border-b border-gray-800">
      <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Products</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Solutions</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Customers</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Resources</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Pricing</a>
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium hover:bg-gray-800">Careers</a>
        <div class="pt-4 flex flex-col space-y-2">
            <a href="#" class="block px-3 py-2 text-center rounded-md text-base font-medium hover:bg-gray-800">Sign in</a>
            <a href="#" class="block px-3 py-2 text-center rounded-md text-base font-medium bg-ramp-yellow text-ramp-dark">See a demo</a>
        </div>
      </div>
    </div>
  {/if}
</nav>
