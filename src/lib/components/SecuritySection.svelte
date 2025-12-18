<script>
    import { Shield, FileText, AlertCircle, CheckCircle } from 'lucide-svelte';
</script>

<section id="safety" class="bg-[#111111] text-white py-24">
    <div class="mx-auto max-w-7xl px-4 sm:px-6 lg:px-8">
        <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
            <!-- Left Content -->
            <div class="flex flex-col justify-center">
                <div class="flex items-center gap-2 mb-8">
                    <Shield size={16} class="text-white" />
                    <span class="text-xs font-mono uppercase tracking-widest text-gray-400">Safety & Transparency</span>
                </div>

                <h2 class="text-4xl md:text-5xl font-serif mb-2">Regulated, Transparent,</h2>
                <h2 class="text-4xl md:text-5xl font-serif mb-12">Fully Disclosed</h2>

                <div class="space-y-4 mb-12">
                    <div class="flex items-center gap-3">
                        <Shield size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Regulated exchange execution (CME Group)</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <FileText size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Comprehensive risk disclosures provided</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <AlertCircle size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">Margin call, interest-rate & liquidity risks documented</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <CheckCircle size={16} class="text-gray-400" />
                        <span class="text-sm font-medium">US residents only, privacy policy active</span>
                    </div>
                </div>

                <div class="text-xs text-gray-400 leading-relaxed border-t border-gray-800 pt-6">
                    <p class="mb-2">
                        <strong class="text-white">Important Disclosure:</strong> Kubence, LLC does not provide tax, legal, or accounting advice. All materials are for informational purposes only.
                    </p>
                    <p>
                        Consult your own tax, legal, and financial advisors before engaging in any transactions. Box spread financing involves risks including margin calls, interest-rate fluctuations, and liquidity constraints.
                    </p>
                </div>
            </div>

            <!-- Right Content: Compliance Grid -->
            <div class="grid grid-cols-2 border-t border-l border-gray-800">
                <!-- CME Group -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                        <div class="text-center">
                            <div class="text-xl font-bold">CME</div>
                            <div class="text-[10px]">Group</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Exchange</span>
                </div>

                <!-- OCC -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                        <div class="text-center">
                            <div class="text-xl font-bold">OCC</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Clearing</span>
                </div>

                <!-- Section 1256 -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="h-24 w-24 rounded-full border-2 border-gray-600 flex items-center justify-center mb-4 opacity-70 group-hover:opacity-100 transition-opacity">
                         <div class="text-center">
                            <div class="text-sm font-bold">§1256</div>
                        </div>
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Tax Code</span>
                </div>

                <!-- Privacy Policy -->
                <div class="aspect-square border-r border-b border-gray-800 flex flex-col items-center justify-center p-8 relative group">
                    <div class="relative h-20 w-20 opacity-70 group-hover:opacity-100 transition-opacity flex items-center justify-center">
                        <Shield size={48} class="text-gray-400" />
                    </div>
                    <span class="absolute bottom-4 left-4 text-[10px] text-gray-500 font-mono">Privacy 2025</span>
                </div>
            </div>
        </div>
    </div>
</section>
