<script>
    import { ArrowRight, Check } from 'lucide-svelte';
</script>

<section class="py-24 bg-white">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-20">
            <p class="text-gray-500 mb-4 text-sm font-medium">New software shouldn't take a year to implement.</p>
            <h2 class="text-4xl md:text-5xl font-serif mb-6 text-gray-900 tracking-tight max-w-3xl mx-auto leading-tight">
                Here's what you can get done with Ramp in just 30 days.
            </h2>
            <a href="#" class="inline-flex items-center text-gray-900 font-medium hover:opacity-70 transition-opacity mt-2">
                Switch to Ramp <ArrowRight size={16} class="ml-1" />
            </a>
        </div>

        <!-- Timeline Graphic -->
        <div class="relative mb-12 hidden md:block max-w-[900px] mx-auto">
            <div class="absolute top-1/2 left-0 w-full h-px bg-gray-200 -translate-y-1/2 z-0"></div>
            <!-- Progress bar -->
            <div class="absolute top-1/2 left-0 w-1/2 h-px bg-gray-300 -translate-y-1/2 z-0"></div>
            
            <div class="flex justify-between relative z-10">
                <div class="bg-white px-6 py-2 text-sm font-medium text-gray-500 border border-gray-200 rounded-full shadow-sm">Today</div>
                <div class="bg-white px-6 py-2 text-sm font-medium text-gray-500 border border-gray-200 rounded-full shadow-sm">Day 5</div>
                <div class="bg-white px-6 py-2 text-sm font-medium text-gray-500 border border-gray-200 rounded-full shadow-sm">Day 30</div>
            </div>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Col 1 -->
            <div class="bg-ramp-card p-8 rounded-xl border border-gray-100 hover:shadow-md transition-shadow">
                <h3 class="font-semibold text-lg mb-6">Get started</h3>
                <ul class="space-y-4">
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Connect your ERP in five minutes</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Upload your policy in two minutes</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Issue your first card in one minute</span>
                    </li>
                </ul>
            </div>

            <!-- Col 2 -->
            <div class="bg-ramp-card p-8 rounded-xl border border-gray-100 hover:shadow-md transition-shadow">
                <h3 class="font-semibold text-lg mb-6">Get comfortable</h3>
                <ul class="space-y-4">
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Connect to HRIS, email, and 200+ apps</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Set up approvals and controls</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Issue cards to employees</span>
                    </li>
                </ul>
            </div>

            <!-- Col 3 -->
            <div class="bg-ramp-card p-8 rounded-xl border border-gray-100 hover:shadow-md transition-shadow">
                <h3 class="font-semibold text-lg mb-6">Ask why you didn't switch years ago</h3>
                <ul class="space-y-4">
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">100% of business spend moved to Ramp</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Intake-to-pay 8.5x more efficient</span>
                    </li>
                    <li class="flex items-start gap-3">
                        <Check size={16} class="text-gray-400 mt-1 flex-shrink-0" />
                        <span class="text-gray-600 text-sm leading-relaxed">Books close 75% faster</span>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</section>
