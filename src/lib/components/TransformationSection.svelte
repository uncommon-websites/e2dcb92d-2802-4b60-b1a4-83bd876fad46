<script>
    import { TrendingUp, Shield, DollarSign, CheckCircle } from 'lucide-svelte';
</script>

<section id="how-it-works" class="py-24 bg-white">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="mb-20">
            <h2 class="text-4xl md:text-5xl font-serif text-gray-900 leading-tight max-w-4xl">
                Box spread financing has been used by <span class="font-semibold">institutional investors for over 50 years.</span> Now available to you.
            </h2>
        </div>

        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16 items-center">
            <!-- Left: Image -->
            <div class="relative">
                <div class="relative rounded-lg overflow-hidden shadow-2xl aspect-[4/3]">
                    <img 
                        src="/generated/image-professional-wealth-advisor-meeting-with-1766088361374-1.webp" 
                        alt="Professional wealth advisory" 
                        class="absolute inset-0 w-full h-full object-cover"
                    />
                </div>
            </div>

            <!-- Right: Features List -->
            <div class="space-y-12">
                <h3 class="text-2xl font-serif text-gray-900">
                    Access Liquidity While<br/>Keeping Your Investments
                </h3>

                <div class="space-y-8">
                    {#each [
                        { id: '01', title: 'Apply with your investment portfolio', icon: TrendingUp },
                        { id: '02', title: 'We execute box spreads on regulated exchanges', icon: Shield },
                        { id: '03', title: 'Receive funds at SOFR + 0.5% rates', icon: DollarSign },
                        { id: '04', title: 'No capital gains tax triggered', icon: CheckCircle }
                    ] as feature}
                        <div class="flex items-start gap-4 group cursor-pointer">
                            <div class="flex-shrink-0 relative">
                                <div class="h-10 w-10 rounded-full border border-gray-200 flex items-center justify-center text-xs font-mono text-gray-500 group-hover:border-black group-hover:text-black transition-colors bg-white z-10 relative">
                                    {feature.id}
                                </div>
                                {#if feature.id !== '04'}
                                    <div class="absolute top-10 left-1/2 -translate-x-1/2 w-px h-8 bg-gray-100 -z-0"></div>
                                {/if}
                            </div>
                            <div class="pt-2">
                                <h4 class="text-lg text-gray-600 group-hover:text-gray-900 transition-colors font-light">
                                    {feature.title}
                                </h4>
                            </div>
                        </div>
                    {/each}
                </div>
            </div>
        </div>
    </div>
</section>
