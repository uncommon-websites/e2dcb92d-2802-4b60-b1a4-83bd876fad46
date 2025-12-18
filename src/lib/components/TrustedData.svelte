<script>
    const locations = [
        { city: "Palo Alto", state: "CA" },
        { city: "San Francisco", state: "CA" },
        { city: "Los Angeles", state: "CA" },
        { city: "New York City", state: "NY" }
    ];
</script>

<section id="benefits" class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-16 max-w-3xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-serif text-gray-900 mb-6">Why Kubence</h2>
            <p class="text-lg text-gray-600 leading-relaxed">
                We bring institutional box spread financing to high-net-worth investors, combining 50+ years of market-proven strategy with modern execution and CPA-validated tax advantages.
            </p>
        </div>

        <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-16">
            <div class="text-center">
                <div class="text-5xl font-serif text-gray-900 mb-3">SOFR + 0.5%</div>
                <div class="text-sm font-medium text-gray-600 mb-2">Transparent Rates</div>
                <div class="text-xs text-gray-500 leading-relaxed">Institutional pricing without custodial intermediary fees</div>
            </div>
            <div class="text-center">
                <div class="text-5xl font-serif text-gray-900 mb-3">60/40</div>
                <div class="text-sm font-medium text-gray-600 mb-2">Tax Treatment</div>
                <div class="text-xs text-gray-500 leading-relaxed">Section 1256 long-term/short-term capital gains split</div>
            </div>
            <div class="text-center">
                <div class="text-5xl font-serif text-gray-900 mb-3">50+</div>
                <div class="text-sm font-medium text-gray-600 mb-2">Years Proven</div>
                <div class="text-xs text-gray-500 leading-relaxed">Used by hedge funds and family offices since the 1970s</div>
            </div>
            <div class="text-center">
                <div class="text-5xl font-serif text-gray-900 mb-3">$2T</div>
                <div class="text-sm font-medium text-gray-600 mb-2">Market Size</div>
                <div class="text-xs text-gray-500 leading-relaxed">Securities-backed lending market opportunity</div>
            </div>
        </div>

        <div class="border-t border-gray-200 pt-16">
            <h3 class="text-xl font-serif text-gray-900 mb-8 text-center">Multi-City Presence</h3>
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                {#each locations as location}
                    <div class="flex flex-col items-center gap-2 p-4 bg-gray-50 rounded-lg">
                        <div class="h-12 w-12 rounded-full bg-black flex items-center justify-center text-white text-xs font-bold">
                            {location.state}
                        </div>
                        <span class="text-sm font-medium text-gray-900">{location.city}</span>
                    </div>
                {/each}
            </div>
        </div>
    </div>
</section>
