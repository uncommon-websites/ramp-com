<script>
    import { ArrowRight } from 'lucide-svelte';
</script>

<section class="py-32 bg-white">
    <div class="max-w-[1200px] mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-24 max-w-3xl mx-auto">
            <h2 class="text-4xl md:text-5xl font-serif mb-6 text-gray-900 tracking-tight leading-tight">
                For startups, global enterprises, and everyone in between.
            </h2>
            <p class="text-gray-500 text-lg">
                Simple defaults, direct integrations, and advanced customization means Ramp will scale with you.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Card 1 -->
            <div class="bg-ramp-card rounded-2xl p-8 md:p-12 h-[500px] flex flex-col justify-between group hover:shadow-xl transition-shadow">
                <div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Completely flexible.</h3>
                    <p class="text-gray-500 mb-8 max-w-sm">Customize Ramp to fit your business and give you the controls you need with policies, roles, and approval workflows.</p>
                </div>
                <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-6 flex-1 w-full relative overflow-hidden flex flex-col justify-center">
                    <div class="space-y-6 w-full max-w-xs mx-auto">
                         <div class="flex items-center justify-between p-3 bg-gray-50 rounded border border-gray-100">
                            <div class="flex items-center gap-3">
                                <div class="w-8 h-8 rounded-full bg-gray-200"></div>
                                <div class="h-2 w-24 bg-gray-200 rounded"></div>
                            </div>
                            <div class="w-10 h-5 bg-green-500 rounded-full relative">
                                <div class="absolute right-0.5 top-0.5 w-4 h-4 bg-white rounded-full shadow-sm"></div>
                            </div>
                         </div>
                         
                         <div class="p-4 bg-gray-50 rounded-lg border border-gray-100">
                            <div class="flex justify-between mb-2">
                                <span class="text-xs font-bold text-gray-400 uppercase">Spending Limit</span>
                            </div>
                            <div class="h-2 w-full bg-gray-200 rounded-full overflow-hidden">
                                <div class="h-full w-2/3 bg-green-500"></div>
                            </div>
                         </div>
                    </div>
                </div>
            </div>

            <!-- Card 2 -->
            <div class="bg-ramp-card rounded-2xl p-8 md:p-12 h-[500px] flex flex-col justify-between group hover:shadow-xl transition-shadow">
                <div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">An extension of your team.</h3>
                    <p class="text-gray-500 mb-8 max-w-sm">Get dedicated support anytime, anywhere. We're always ready to help.</p>
                </div>
                <div class="bg-[#eef2ff] rounded-xl p-6 flex-1 w-full relative flex items-center justify-center">
                     <div class="bg-white p-6 rounded-2xl shadow-lg max-w-[280px] w-full relative">
                        <div class="text-lg font-medium text-gray-900 mb-2">How can I help?</div>
                        <div class="flex items-center gap-3 mt-4">
                            <div class="w-8 h-8 rounded-full overflow-hidden bg-blue-500">
                                <!-- Avatar placeholder -->
                                <svg viewBox="0 0 24 24" class="w-full h-full text-white fill-current"><circle cx="12" cy="8" r="4"/><path d="M4 20c0-4.4 3.6-8 8-8s8 3.6 8 8"/></svg>
                            </div>
                            <span class="text-sm text-gray-500 font-medium">Nathan, Ramp</span>
                        </div>
                     </div>
                     <div class="absolute bottom-8 right-12 bg-white px-3 py-2 rounded-full shadow-md">
                        <div class="flex gap-1">
                            <div class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce"></div>
                            <div class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce delay-100"></div>
                            <div class="w-1.5 h-1.5 bg-gray-400 rounded-full animate-bounce delay-200"></div>
                        </div>
                     </div>
                </div>
            </div>

            <!-- Card 3 -->
            <div class="bg-ramp-card rounded-2xl p-8 md:p-12 h-[500px] flex flex-col justify-between group hover:shadow-xl transition-shadow">
                <div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Integrate and stay synced.</h3>
                    <p class="text-gray-500 mb-8 max-w-sm">Seamlessly integrate Ramp with your accounting systems and consolidate your finance stack.</p>
                </div>
                <div class="flex-1 w-full flex items-center justify-center relative">
                     <!-- Sage Logo -->
                     <div class="w-32 h-32 bg-white rounded-2xl shadow-sm flex items-center justify-center">
                        <span class="text-5xl font-bold text-[#00d639] tracking-tighter">Sage</span>
                     </div>
                     <!-- Decorative elements -->
                     <div class="absolute top-1/2 left-10 w-12 h-1 bg-gray-200 rounded"></div>
                     <div class="absolute top-1/2 right-10 w-12 h-1 bg-gray-200 rounded"></div>
                </div>
            </div>

            <!-- Card 4 -->
            <div class="bg-ramp-card rounded-2xl p-8 md:p-12 h-[500px] flex flex-col justify-between group hover:shadow-xl transition-shadow">
                <div>
                    <h3 class="text-xl font-bold text-gray-900 mb-4">Operate globally.</h3>
                    <p class="text-gray-500 mb-8 max-w-sm">Send payments to 195 countries in over 40 currencies and reimburse employees in their local currencies within 2 days.</p>
                </div>
                <div class="bg-white rounded-xl shadow-sm border border-gray-100 p-6 flex-1 w-full flex flex-col justify-center gap-4">
                     <div class="flex justify-between items-center p-3 hover:bg-gray-50 rounded transition-colors cursor-pointer">
                        <span class="font-mono text-lg text-gray-900 font-bold">£550</span>
                        <div class="flex items-center gap-3">
                            <span class="text-xs text-gray-400 font-mono">1.26%</span>
                            <span class="bg-[#fef9c3] text-[#854d0e] text-[10px] px-2 py-1 rounded font-bold tracking-wider">GBP</span>
                        </div>
                     </div>
                     <div class="flex justify-between items-center p-3 hover:bg-gray-50 rounded transition-colors cursor-pointer">
                        <span class="font-mono text-lg text-gray-900 font-bold">€230</span>
                        <div class="flex items-center gap-3">
                            <span class="text-xs text-gray-400 font-mono">1.09%</span>
                            <span class="bg-[#dbeafe] text-[#1e40af] text-[10px] px-2 py-1 rounded font-bold tracking-wider">EUR</span>
                        </div>
                     </div>
                     <div class="flex justify-between items-center p-3 hover:bg-gray-50 rounded transition-colors cursor-pointer">
                        <span class="font-mono text-lg text-gray-900 font-bold">¥11,717</span>
                        <div class="flex items-center gap-3">
                            <span class="text-xs text-gray-400 font-mono">147.23%</span>
                            <span class="bg-[#fee2e2] text-[#991b1b] text-[10px] px-2 py-1 rounded font-bold tracking-wider">YEN</span>
                        </div>
                     </div>
                </div>
            </div>
        </div>
    </div>
</section>
