<script lang="ts">
  import { onMount } from 'svelte';
  
  let visible = false;
  
  onMount(() => {
    const handleScroll = () => {
      // Show after scrolling past hero
      visible = window.scrollY > 600;
    };
    window.addEventListener('scroll', handleScroll);
    return () => window.removeEventListener('scroll', handleScroll);
  });
</script>

<div class="fixed bottom-0 left-0 right-0 bg-ramp-dark border-t border-gray-800 p-4 z-40 transition-transform duration-300 {visible ? 'translate-y-0' : 'translate-y-full'}">
  <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-4">
    <p class="text-white font-medium text-sm md:text-base">Join the 50,000+ businesses saving their finances with Ramp.</p>
    
    <form class="flex w-full md:w-auto gap-2">
      <input 
        type="email" 
        placeholder="What's your work email?" 
        class="flex-1 md:w-64 px-3 py-2 rounded bg-gray-800 border border-gray-700 text-white placeholder-gray-500 focus:outline-none focus:ring-1 focus:ring-ramp-green text-sm"
      />
      <button type="submit" class="bg-ramp-green text-black px-4 py-2 rounded font-semibold hover:bg-[#c3e83f] transition-colors text-sm whitespace-nowrap">
        Get started for free
      </button>
    </form>
  </div>
</div>
