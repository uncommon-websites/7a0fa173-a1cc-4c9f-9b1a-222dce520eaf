<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-tangible-dark)] min-h-screen flex flex-col">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Notification Pill -->
                    <div class="inline-flex items-center gap-2 bg-white/10 backdrop-blur-sm border border-white/10 rounded-full px-4 py-1.5 mb-8">
                        <span class="w-2 h-2 rounded-full bg-[var(--color-tangible-primary)]"></span>
                        <span class="text-white text-sm font-medium">300,000+ Users Scaled</span>
                        <span class="text-gray-400 text-sm">on a single LMS</span>
                        <svg class="w-4 h-4 text-gray-400" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"></path></svg>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance">
                        WordPress LMS hosting that actually performs.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Specialized hosting for LearnDash, LifterLMS, and Sensei. Built by LMS experts who've scaled platforms to 300,000+ concurrent users. Faster or it's FREE.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="bg-white hover:bg-gray-100 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            Start Free Migration
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bg-transparent border border-white/20 hover:bg-white/10 text-white px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2">
                            View Plans
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Image -->
            <div class="mt-20 relative">
                <div class="container mx-auto px-6">
                    <div class="max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-white/10">
                        <img src="/generated/image-professional-web-developer-working-on-a--1765484922549-0.webp" alt="Course creator working on WordPress LMS" class="w-full h-auto" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Partners Section -->
        <section class="py-12 border-y border-white/5 bg-black/20">
            <div class="container mx-auto px-6">
                <p class="text-center text-gray-500 text-sm mb-8">Trusted by leading LMS platforms</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20 opacity-60">
                    <!-- LearnDash -->
                    <div class="text-white font-bold text-xl tracking-tight">LearnDash</div>
                    <!-- LifterLMS -->
                    <div class="text-white font-bold text-xl tracking-tight">LifterLMS</div>
                    <!-- Uncanny Owl -->
                    <div class="text-white font-bold text-xl tracking-tight">Uncanny Owl</div>
                    <!-- Sensei -->
                    <div class="text-white font-bold text-xl tracking-tight">Sensei</div>
                    <!-- CloudFlare -->
                    <div class="text-white font-bold text-xl tracking-tight">Cloudflare</div>
                </div>
            </div>
        </section>

        <!-- Performance Guarantee Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <h2 class="text-[var(--color-tangible-primary)] font-mono text-xs tracking-[0.2em] uppercase mb-6">Performance Guarantee</h2>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Faster or it's FREE.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">No gimmicks. Just results.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Image -->
                    <div class="rounded-3xl overflow-hidden shadow-2xl border border-white/10">
                        <img src="/generated/image-students-engaging-with-online-learning-o-1765484927521-2.webp" alt="Students learning online" class="w-full h-full object-cover" />
                    </div>

                    <!-- Text Content -->
                    <div class="space-y-8">
                        <h3 class="text-4xl md:text-5xl font-bold text-white tracking-tight">Real power. Not buzzwords.</h3>
                        <p class="text-gray-400 text-lg leading-relaxed max-w-lg">
                            We focus on raw processing power and LMS-specific optimizations that actually work for logged-in students. Not fancy caching techniques that fail when it matters most.
                        </p>
                        <div class="space-y-4">
                            <div class="flex items-start gap-3">
                                <div class="w-6 h-6 rounded-full bg-[var(--color-tangible-primary)]/20 flex items-center justify-center flex-shrink-0 mt-0.5">
                                    <svg class="w-3 h-3 text-[var(--color-tangible-primary)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                                </div>
                                <div>
                                    <p class="text-white font-semibold">40% to 10X faster</p>
                                    <p class="text-gray-400 text-sm">Documented improvements vs. Kinsta, WP Engine, Cloudways</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="w-6 h-6 rounded-full bg-[var(--color-tangible-primary)]/20 flex items-center justify-center flex-shrink-0 mt-0.5">
                                    <svg class="w-3 h-3 text-[var(--color-tangible-primary)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                                </div>
                                <div>
                                    <p class="text-white font-semibold">300,000+ concurrent users</p>
                                    <p class="text-gray-400 text-sm">Successfully scaled for non-profit client</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="w-6 h-6 rounded-full bg-[var(--color-tangible-primary)]/20 flex items-center justify-center flex-shrink-0 mt-0.5">
                                    <svg class="w-3 h-3 text-[var(--color-tangible-primary)]" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"/></svg>
                                </div>
                                <div>
                                    <p class="text-white font-semibold">Enterprise CDN included</p>
                                    <p class="text-gray-400 text-sm">Cloudflare Enterprise on all plans</p>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- White Section -->
        <div class="bg-[#F9FAFB] text-black rounded-t-[4rem] relative z-20 mt-[-2rem] pt-32 pb-32">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="h-px w-12 bg-gray-300"></div>
                        <span class="text-gray-500 font-mono text-xs tracking-[0.2em] uppercase">LMS-Optimized Infrastructure</span>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything your LMS needs to thrive.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Nothing it doesn't.</h2>
                    
                    <a href="#" class="inline-flex items-center gap-2 text-sm font-semibold border-b border-black pb-0.5 hover:text-gray-600 transition-colors">
                        View all features
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </a>
                </div>

                <!-- Features Grid -->
                <div class="flex flex-col lg:flex-row gap-12">
                    <!-- Sidebar Navigation (Sticky) -->
                    <div class="hidden lg:block w-64 flex-shrink-0">
                        <div class="sticky top-32 space-y-4">
                            <div class="flex items-center gap-2 text-sm font-semibold text-black border-l-2 border-black pl-4 py-1">
                                <span class="w-1.5 h-1.5 rounded-full bg-[var(--color-tangible-primary)]"></span>
                                Performance
                            </div>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Expert Migration</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Staging Sites</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">LMS Support</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Security</a>
                            <a href="#" class="block text-sm text-gray-500 pl-4 py-1 hover:text-black border-l-2 border-transparent hover:border-gray-200 transition-colors">Monitoring</a>
                        </div>
                    </div>

                    <!-- Feature Cards -->
                    <div class="flex-grow space-y-8">
                        <FeatureRow 
                            title="Performance" 
                            description="Raw power that works. We prioritize processing power and database optimization over fancy caching that breaks for logged-in students. Your LMS performs under real-world load."
                            icon="data"
                            image="data"
                        />
                         <FeatureRow 
                            title="Expert Migration" 
                            description="Free white-glove service. Our team of LMS experts handles your migration personally—not a plugin. We've migrated hundreds of sites and know every edge case."
                            icon="connect"
                            image="connect"
                        />
                         <FeatureRow 
                            title="Staging Sites" 
                            description="Two full-power environments. Test plugins, themes, and updates on staging sites with the same resources as production. Not reduced-performance testing environments."
                            icon="preview"
                            image="preview"
                        />
                         <FeatureRow 
                            title="LMS Support" 
                            description="Experts who understand LMS. Our support team includes actual LearnDash plugin developers. We won't tell you to uninstall your LMS to fix performance issues."
                            icon="guard"
                            image="guard"
                        />
                         <FeatureRow 
                            title="Security" 
                            description="Enterprise-grade protection. Grade A SSL, enterprise firewall, malware scanning at CDN edge. Security handled at infrastructure level, not flaky plugins."
                            icon="lock"
                            image="collateral"
                        />
                         <FeatureRow 
                            title="Monitoring" 
                            description="Know what's happening. New Relic integration on all plans. Custom profiling tools to diagnose LMS-specific performance issues before they impact students."
                            icon="lab"
                            image="lab"
                        />
                    </div>
                </div>

                <!-- Agency Services Section -->
                <div class="mt-32 text-center max-w-4xl mx-auto mb-24">
                    <div class="w-24 h-24 mx-auto bg-gradient-to-br from-blue-100 to-purple-100 rounded-full flex items-center justify-center mb-8 relative">
                        <div class="absolute inset-0 bg-white/50 blur-xl rounded-full"></div>
                        <svg class="w-10 h-10 text-blue-600 relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Need custom development? We've been building LMS sites since 2016.
                    </h2>
                    <p class="text-gray-600 mb-8 text-lg">Official LearnDash development partner. Creators of BeaverDash, MemberDash, and Loops & Logic.</p>
                    <button class="bg-white border border-gray-200 hover:border-gray-400 text-black px-6 py-3 rounded-full font-medium transition-colors flex items-center gap-2 mx-auto">
                        Explore agency services
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <p class="text-xl text-gray-500 mb-12">Trusted by course creators worldwide. Real results from real customers.</p>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Influential U Card (Large) -->
                        <div class="md:col-span-2 bg-[#0A0A0A] rounded-3xl p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute inset-0 bg-gradient-to-t from-black via-black/50 to-transparent"></div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="text-white font-bold text-2xl tracking-tight">Influential U</div>
                                    <div class="w-8 h-8 rounded-full bg-[var(--color-tangible-primary)] flex items-center justify-center text-black font-bold">✓</div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-6 max-w-md">
                                    "Saved $470/month while getting better performance"
                                </h3>
                                <p class="text-gray-400 text-lg mb-4 max-w-lg">
                                    78% cost reduction compared to previous hosting, with immediate speed improvements and expert support.
                                </p>
                                <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Massage Mastery Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-blue-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold text-lg mb-2">Massage Mastery Online</p>
                                    <p class="text-gray-400 text-sm">"Immediate speed increase upon migration"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                            <!-- Autism Double-Checked Card -->
                            <div class="bg-[#0A0A0A] rounded-3xl p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute inset-0 bg-gradient-to-br from-green-900/40 to-black"></div>
                                <div class="relative z-10">
                                    <p class="text-white font-semibold text-lg mb-2">Autism Double-Checked</p>
                                    <p class="text-gray-400 text-sm">"Understanding our needs and urgent response times"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <div class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md border border-white/20 flex items-center justify-center text-white group-hover:bg-white group-hover:text-black transition-colors">
                                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="bg-[#0A0A0A] rounded-3xl p-12 md:p-20 relative overflow-hidden mb-32 text-center">
                    <div class="absolute inset-0 bg-[url('/grid-pattern.svg')] opacity-10"></div>
                    <div class="absolute left-0 top-0 w-64 h-64 bg-[var(--color-tangible-primary)]/10 blur-[100px] rounded-full"></div>
                    <div class="absolute right-0 bottom-0 w-64 h-64 bg-blue-500/10 blur-[100px] rounded-full"></div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Expert LMS hosting. <span class="text-[var(--color-tangible-primary)]">Zero compromises.</span>
                        </h2>
                        <p class="text-gray-400 mb-10 text-lg">
                            From $29/month. Free expert migration. Two staging sites. 24/7 support from actual LMS developers.
                        </p>
                        <button class="bg-white hover:bg-gray-100 text-black px-8 py-3 rounded-full font-semibold transition-colors">
                            View Pricing
                        </button>
                    </div>
                </div>

                <!-- Notable Clients -->
                <div class="text-center mb-32">
                    <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                        Trusted by organizations<br>
                        <span class="text-gray-400">from startups to Fortune 500</span>
                    </h2>
                    <button class="bg-gray-100 hover:bg-gray-200 text-black px-6 py-2 rounded-full text-sm font-medium transition-colors flex items-center gap-2 mx-auto mb-16 mt-8">
                        View all case studies
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-px bg-gray-200 border border-gray-200 rounded-2xl overflow-hidden">
                        {#each ['Intuit QuickBooks', 'Cox Campus', 'University of Ottawa', 'CDC', 'KIPP DC Schools', 'Uncanny Owl', 'LearnDash', 'LifterLMS'] as client}
                        <div class="bg-[#F9FAFB] p-12 flex items-center justify-center opacity-60 hover:opacity-100 transition-all duration-300">
                            <span class="font-semibold text-base text-center">{client}</span>
                        </div>
                        {/each}
                    </div>
                </div>

                <!-- Blog Section -->
                <div class="mb-12">
                    <h2 class="text-4xl font-bold text-gray-900 mb-12">Learn more about WordPress LMS optimization.</h2>
                    <div class="grid md:grid-cols-2 gap-8">
                        <!-- Post 1 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gradient-to-br from-gray-200 to-gray-300 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden">
                                <img src="/generated/image-happy-online-course-creator-smiling-whil-1765484925157-1.webp" alt="Course creator" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Case Study</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">How we scaled LearnDash to 300,000+ concurrent users</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="bg-gray-100 rounded-3xl aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <img src="/generated/image-technical-support-specialist-with-headse-1765484929745-3.webp" alt="Support specialist" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-bold text-gray-500 uppercase tracking-wider mb-2">Technical Guide</div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-blue-600 transition-colors">Why generic WordPress hosting fails for LMS sites</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

