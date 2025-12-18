<script>
    import { Plane, Home, Anchor } from 'lucide-svelte';
</script>

<section class="py-24 bg-gray-50">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight">
                Finance Your Lifestyle<br />Without Liquidating Assets
            </h2>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
            <!-- Card 1: Real Estate & Construction -->
            <div class="group bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-lg transition-shadow">
                <div class="p-8 aspect-[4/3] flex flex-col items-center justify-center bg-gradient-to-br from-gray-50 to-white">
                    <div class="h-20 w-20 rounded-full bg-black flex items-center justify-center mb-6">
                        <Home size={32} class="text-white" />
                    </div>
                    <div class="text-center">
                        <div class="text-6xl font-serif text-gray-900 mb-2">$2M+</div>
                        <div class="text-sm text-gray-500">Typical Loan Size</div>
                    </div>
                </div>
                <div class="p-6 border-t border-gray-100">
                    <h3 class="text-xl font-serif text-gray-900 mb-3">Real Estate & Construction</h3>
                    <p class="text-sm text-gray-500 leading-relaxed">
                        Fund major construction projects, property acquisitions, or renovations without selling your investment portfolio. Keep your assets working for you while accessing the capital you need.
                    </p>
                </div>
            </div>

            <!-- Card 2: Luxury Assets -->
            <div class="group bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-lg transition-shadow">
                <div class="p-8 aspect-[4/3] flex flex-col items-center justify-center bg-gradient-to-br from-gray-50 to-white">
                    <div class="h-20 w-20 rounded-full bg-black flex items-center justify-center mb-6">
                        <Anchor size={32} class="text-white" />
                    </div>
                    <div class="text-center">
                        <div class="text-6xl font-serif text-gray-900 mb-2">0%</div>
                        <div class="text-sm text-gray-500">Capital Gains Tax</div>
                    </div>
                </div>
                <div class="p-6 border-t border-gray-100">
                    <h3 class="text-xl font-serif text-gray-900 mb-3">Yachts & Luxury Assets</h3>
                    <p class="text-sm text-gray-500 leading-relaxed">
                        Purchase yachts, luxury vehicles, or other high-value assets while maintaining your investment positions. Avoid triggering capital gains taxes that traditional liquidation would require.
                    </p>
                </div>
            </div>

            <!-- Card 3: Private Aviation -->
            <div class="group bg-white rounded-lg overflow-hidden shadow-sm hover:shadow-lg transition-shadow">
                <div class="p-8 aspect-[4/3] flex flex-col items-center justify-center bg-gradient-to-br from-gray-50 to-white">
                    <div class="h-20 w-20 rounded-full bg-black flex items-center justify-center mb-6">
                        <Plane size={32} class="text-white" />
                    </div>
                    <div class="text-center">
                        <div class="text-6xl font-serif text-gray-900 mb-2">50%</div>
                        <div class="text-sm text-gray-500">Loan-to-Value</div>
                    </div>
                </div>
                <div class="p-6 border-t border-gray-100">
                    <h3 class="text-xl font-serif text-gray-900 mb-3">Private Aviation</h3>
                    <p class="text-sm text-gray-500 leading-relaxed">
                        Finance private aircraft purchases with institutional rates. Access up to 50% of your non-retirement portfolio value while your investments continue to grow and compound.
                    </p>
                </div>
            </div>
        </div>
    </div>
</section>
