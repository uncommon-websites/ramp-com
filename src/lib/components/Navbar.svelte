<script lang="ts">
  import { onMount } from 'svelte';

  let isScrolled = false;

  onMount(() => {
    const handleScroll = () => {
      isScrolled = window.scrollY > 10;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-colors duration-300 {isScrolled ? 'bg-ramp-dark/90 backdrop-blur-md' : 'bg-transparent'} text-white py-4 px-6 md:px-8 border-b border-white/10">
  <div class="max-w-7xl mx-auto flex items-center justify-between">
    <div class="flex items-center gap-8">
      <a href="/" class="text-2xl font-bold flex items-center gap-1">
        Ramp
        <svg viewBox="0 0 24 24" fill="currentColor" class="w-3 h-3 text-ramp-green rotate-45">
            <path d="M12 0L24 12L12 24L0 12L12 0Z" />
        </svg>
      </a>
      
      <div class="hidden lg:flex items-center gap-6 text-sm font-medium text-gray-300">
        <button class="hover:text-white flex items-center gap-1">Products <span class="text-[10px]">▼</span></button>
        <button class="hover:text-white flex items-center gap-1">Solutions <span class="text-[10px]">▼</span></button>
        <a href="#" class="hover:text-white">Customers</a>
        <button class="hover:text-white flex items-center gap-1">Resources <span class="text-[10px]">▼</span></button>
        <a href="#" class="hover:text-white">Pricing</a>
      </div>
    </div>

    <div class="flex items-center gap-6 text-sm font-medium">
      <a href="#" class="hidden lg:block hover:text-white text-gray-300">Careers</a>
      <a href="#" class="hover:text-white text-white">Sign in</a>
      <a href="#" class="bg-ramp-green text-black px-4 py-2 rounded-md hover:bg-[#c3e83f] transition-colors font-semibold">See a demo</a>
    </div>
  </div>
</nav>
