<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Footer from '$lib/components/Footer.svelte';
    import FeatureRow from '$lib/components/FeatureRow.svelte';
</script>

<div class="bg-[var(--color-tangible-dark)] min-h-screen flex flex-col grid-pattern">
    <Navbar />

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative pt-32 pb-20 overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="max-w-4xl mx-auto text-center">
                    <!-- Status Indicator -->
                    <div class="inline-flex items-center gap-3 control-panel px-5 py-2 mb-8">
                        <div class="status-light status-light-green"></div>
                        <span class="crt-text text-xs uppercase tracking-wider">System Status: Operational</span>
                        <div class="h-3 w-px bg-[var(--color-metal)]"></div>
                        <span class="crt-text text-xs">300,000+ Users Scaled</span>
                        <div class="h-3 w-px bg-[var(--color-metal)]"></div>
                        <span class="text-[var(--color-crt-green-dim)] text-xs font-mono">SINGLE LMS</span>
                    </div>

                    <h1 class="text-5xl md:text-7xl font-bold text-white tracking-tight mb-6 text-balance" style="font-family: var(--font-sans);">
                        WordPress LMS hosting that actually performs.
                    </h1>
                    
                    <p class="text-lg md:text-xl text-gray-400 mb-10 max-w-2xl mx-auto leading-relaxed text-balance">
                        Specialized hosting for LearnDash, LifterLMS, and Sensei. Built by LMS experts who've scaled platforms to 300,000+ concurrent users. Faster or it's FREE.
                    </p>
                    
                    <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                        <button class="switch-button text-white px-8 py-4 font-medium flex items-center gap-3 uppercase tracking-wider text-sm">
                            <span class="status-light status-light-green"></span>
                            Start Free Migration
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                        <button class="bevel-inset bg-[var(--color-panel-dark)] text-[var(--color-crt-green)] px-8 py-4 font-mono text-sm uppercase tracking-wider flex items-center gap-3 hover:bg-[var(--color-panel-medium)] transition-colors">
                            View Plans
                            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                                <path d="M5 12h14M12 5l7 7-7 7"/>
                            </svg>
                        </button>
                    </div>
                </div>
            </div>

            <!-- Hero Image - CRT Monitor Style -->
            <div class="mt-20 relative">
                <div class="container mx-auto px-6">
                    <div class="max-w-5xl mx-auto crt-screen overflow-hidden relative">
                        <!-- Monitor bezel -->
                        <div class="absolute top-4 right-4 z-20 flex gap-2">
                            <div class="status-light status-light-green"></div>
                            <div class="status-light status-light-amber"></div>
                        </div>
                        <div class="absolute bottom-4 left-4 z-20 font-mono text-[10px] text-[var(--color-crt-green-dim)] uppercase tracking-wider">
                            MONITOR-01 // ACTIVE
                        </div>
                        <img src="/generated/image-professional-web-developer-working-on-a--1765484922549-0.webp" alt="Course creator working on WordPress LMS" class="w-full h-auto relative z-0" />
                    </div>
                </div>
            </div>
        </section>

        <!-- Partners Section -->
        <section class="py-12 border-y border-[var(--color-metal)] bg-[var(--color-panel-dark)]">
            <div class="container mx-auto px-6">
                <p class="text-center crt-text-amber text-xs uppercase tracking-widest mb-8">Integrated Systems</p>
                <div class="flex flex-wrap justify-center items-center gap-12 md:gap-20">
                    <!-- LearnDash -->
                    <div class="control-panel px-6 py-3">
                        <div class="text-[var(--color-crt-green)] font-mono text-sm tracking-wider">LearnDash</div>
                    </div>
                    <!-- LifterLMS -->
                    <div class="control-panel px-6 py-3">
                        <div class="text-[var(--color-crt-green)] font-mono text-sm tracking-wider">LifterLMS</div>
                    </div>
                    <!-- Uncanny Owl -->
                    <div class="control-panel px-6 py-3">
                        <div class="text-[var(--color-crt-green)] font-mono text-sm tracking-wider">Uncanny Owl</div>
                    </div>
                    <!-- Sensei -->
                    <div class="control-panel px-6 py-3">
                        <div class="text-[var(--color-crt-green)] font-mono text-sm tracking-wider">Sensei</div>
                    </div>
                    <!-- CloudFlare -->
                    <div class="control-panel px-6 py-3">
                        <div class="text-[var(--color-crt-green)] font-mono text-sm tracking-wider">Cloudflare</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- Performance Guarantee Section -->
        <section class="py-32 relative overflow-hidden">
            <div class="container mx-auto px-6 relative z-10">
                <div class="text-center mb-24">
                    <div class="inline-flex items-center gap-2 mb-6">
                        <div class="status-light status-light-amber"></div>
                        <h2 class="crt-text-amber text-xs tracking-[0.3em] uppercase">Performance Guarantee</h2>
                    </div>
                    <h3 class="text-4xl md:text-6xl font-bold text-white mb-2 tracking-tight">Faster or it's FREE.</h3>
                    <h3 class="text-4xl md:text-6xl font-bold text-gray-600 tracking-tight">No gimmicks. Just results.</h3>
                </div>

                <div class="grid md:grid-cols-2 gap-16 items-center max-w-6xl mx-auto">
                    <!-- Image - CRT Monitor -->
                    <div class="crt-screen overflow-hidden relative">
                        <div class="absolute top-3 right-3 z-20 flex gap-2">
                            <div class="status-light status-light-green"></div>
                            <div class="status-light status-light-amber"></div>
                        </div>
                        <div class="absolute bottom-3 left-3 z-20 font-mono text-[9px] text-[var(--color-crt-green-dim)] uppercase tracking-wider">
                            MONITOR-02 // PERFORMANCE
                        </div>
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
                                <div class="status-light status-light-green flex-shrink-0 mt-1"></div>
                                <div>
                                    <p class="text-white font-semibold">40% to 10X faster</p>
                                    <p class="text-gray-400 text-sm">Documented improvements vs. Kinsta, WP Engine, Cloudways</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="status-light status-light-green flex-shrink-0 mt-1"></div>
                                <div>
                                    <p class="text-white font-semibold">300,000+ concurrent users</p>
                                    <p class="text-gray-400 text-sm">Successfully scaled for non-profit client</p>
                                </div>
                            </div>
                            <div class="flex items-start gap-3">
                                <div class="status-light status-light-green flex-shrink-0 mt-1"></div>
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
        <div class="bg-[#E5E7EB] text-black relative z-20 mt-[-2rem] pt-32 pb-32 border-t-4 border-[var(--color-metal)]">
            <div class="container mx-auto px-6">
                <!-- Header -->
                <div class="max-w-4xl mb-24">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="panel-divider w-16"></div>
                        <div class="flex items-center gap-2">
                            <div class="status-light status-light-amber"></div>
                            <span class="text-gray-700 font-mono text-xs tracking-[0.3em] uppercase">LMS-Optimized Infrastructure</span>
                        </div>
                    </div>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-900 mb-2 tracking-tight">Everything your LMS needs to thrive.</h2>
                    <h2 class="text-4xl md:text-6xl font-bold text-gray-400 tracking-tight mb-8">Nothing it doesn't.</h2>
                    
                    <button class="bevel bg-white text-black px-6 py-3 text-sm font-mono uppercase tracking-wider hover:bg-gray-100 transition-colors inline-flex items-center gap-2">
                        View all features
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
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
                    <div class="w-24 h-24 mx-auto control-panel flex items-center justify-center mb-8 relative">
                        <div class="absolute top-2 right-2">
                            <div class="status-light status-light-amber"></div>
                        </div>
                        <svg class="w-10 h-10 text-[var(--color-crt-green)] relative z-10" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10 20l4-16m4 4l4 4-4 4M6 16l-4-4 4-4"></path></svg>
                    </div>
                    <h2 class="text-4xl md:text-5xl font-bold text-gray-900 mb-8 leading-tight">
                        Need custom development? We've been building LMS sites since 2016.
                    </h2>
                    <p class="text-gray-600 mb-8 text-lg">Official LearnDash development partner. Creators of BeaverDash, MemberDash, and Loops & Logic.</p>
                    <button class="bevel bg-white text-black px-8 py-4 font-mono text-sm uppercase tracking-wider hover:bg-gray-100 transition-colors inline-flex items-center gap-2">
                        Explore agency services
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>
                </div>

                <!-- Trusted By Section -->
                <div class="mb-32">
                    <div class="flex items-center gap-3 mb-12">
                        <div class="status-light status-light-green"></div>
                        <p class="text-xl text-gray-700 font-mono">Trusted by course creators worldwide. Real results from real customers.</p>
                    </div>
                    
                    <div class="grid md:grid-cols-3 gap-6">
                        <!-- Influential U Card (Large) -->
                        <div class="md:col-span-2 control-panel p-10 relative overflow-hidden group min-h-[400px] flex flex-col justify-between">
                            <div class="absolute top-4 right-4 flex gap-2">
                                <div class="status-light status-light-green"></div>
                                <div class="status-light status-light-amber"></div>
                            </div>
                            
                            <div class="relative z-10">
                                <div class="flex items-center gap-4 mb-6">
                                    <div class="crt-text font-mono text-xl tracking-wider">Influential U</div>
                                    <div class="status-light status-light-green"></div>
                                </div>
                                <h3 class="text-3xl font-bold text-white mb-6 max-w-md">
                                    "Saved $470/month while getting better performance"
                                </h3>
                                <p class="text-gray-400 text-lg mb-4 max-w-lg">
                                    78% cost reduction compared to previous hosting, with immediate speed improvements and expert support.
                                </p>
                                <div class="inline-flex items-center gap-2 bevel-inset bg-[var(--color-panel-dark)] px-4 py-2 text-[var(--color-crt-green)] font-mono text-sm uppercase tracking-wider hover:bg-[var(--color-panel-medium)] transition-colors">
                                    Read Case Study
                                    <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
                                </div>
                            </div>
                        </div>

                        <!-- Smaller Cards -->
                        <div class="space-y-6">
                            <!-- Massage Mastery Card -->
                            <div class="control-panel p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute top-3 right-3 flex gap-2">
                                    <div class="status-light status-light-green"></div>
                                </div>
                                <div class="relative z-10">
                                    <p class="crt-text font-mono text-base mb-2">Massage Mastery Online</p>
                                    <p class="text-gray-400 text-sm">"Immediate speed increase upon migration"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <button class="bevel bg-[var(--color-metal)] text-white px-3 py-2 text-xs uppercase tracking-wider hover:bg-[var(--color-metal-light)] transition-colors">
                                        View
                                    </button>
                                </div>
                            </div>
                            <!-- Autism Double-Checked Card -->
                            <div class="control-panel p-8 relative overflow-hidden group h-[240px] flex flex-col justify-between">
                                <div class="absolute top-3 right-3 flex gap-2">
                                    <div class="status-light status-light-green"></div>
                                </div>
                                <div class="relative z-10">
                                    <p class="crt-text font-mono text-base mb-2">Autism Double-Checked</p>
                                    <p class="text-gray-400 text-sm">"Understanding our needs and urgent response times"</p>
                                </div>
                                <div class="relative z-10 flex justify-end">
                                    <button class="bevel bg-[var(--color-metal)] text-white px-3 py-2 text-xs uppercase tracking-wider hover:bg-[var(--color-metal-light)] transition-colors">
                                        View
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Banner -->
                <div class="control-panel p-12 md:p-20 relative overflow-hidden mb-32 text-center grid-pattern">
                    <div class="absolute top-4 left-4 flex gap-2">
                        <div class="status-light status-light-green"></div>
                        <div class="status-light status-light-amber"></div>
                        <div class="status-light status-light-green"></div>
                    </div>
                    <div class="absolute top-4 right-4 font-mono text-[10px] text-[var(--color-crt-green-dim)] uppercase tracking-wider">
                        SYSTEM READY
                    </div>
                    
                    <div class="relative z-10 max-w-3xl mx-auto">
                        <h2 class="text-4xl md:text-6xl font-bold text-white mb-6 tracking-tight">
                            Expert LMS hosting. <span class="crt-text">Zero compromises.</span>
                        </h2>
                        <p class="text-gray-400 mb-10 text-lg">
                            From $29/month. Free expert migration. Two staging sites. 24/7 support from actual LMS developers.
                        </p>
                        <button class="switch-button text-white px-10 py-4 font-medium uppercase tracking-wider text-sm">
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
                    <button class="bevel bg-white text-black px-6 py-3 text-sm font-mono uppercase tracking-wider hover:bg-gray-100 transition-colors inline-flex items-center gap-2 mb-16 mt-8">
                        View all case studies
                        <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <path d="M5 12h14M12 5l7 7-7 7"/>
                        </svg>
                    </button>

                    <div class="grid grid-cols-2 md:grid-cols-4 gap-2 bg-gray-300">
                        {#each ['Intuit QuickBooks', 'Cox Campus', 'University of Ottawa', 'CDC', 'KIPP DC Schools', 'Uncanny Owl', 'LearnDash', 'LifterLMS'] as client}
                        <div class="bevel bg-white p-12 flex items-center justify-center hover:bg-gray-50 transition-all duration-300">
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
                            <div class="crt-screen aspect-[16/9] mb-6 relative overflow-hidden">
                                <div class="absolute top-3 right-3 z-20 flex gap-2">
                                    <div class="status-light status-light-green"></div>
                                </div>
                                <div class="absolute bottom-3 left-3 z-20 font-mono text-[9px] text-[var(--color-crt-green-dim)] uppercase tracking-wider">
                                    CASE-STUDY-01
                                </div>
                                <img src="/generated/image-happy-online-course-creator-smiling-whil-1765484925157-1.webp" alt="Course creator" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-mono text-gray-500 uppercase tracking-wider mb-2 flex items-center gap-2">
                                <div class="status-light status-light-amber"></div>
                                Case Study
                            </div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-gray-600 transition-colors">How we scaled LearnDash to 300,000+ concurrent users</h3>
                        </div>
                        <!-- Post 2 -->
                        <div class="group cursor-pointer">
                            <div class="crt-screen aspect-[16/9] mb-6 relative overflow-hidden flex items-center justify-center">
                                <div class="absolute top-3 right-3 z-20 flex gap-2">
                                    <div class="status-light status-light-green"></div>
                                </div>
                                <div class="absolute bottom-3 left-3 z-20 font-mono text-[9px] text-[var(--color-crt-green-dim)] uppercase tracking-wider">
                                    TECH-GUIDE-02
                                </div>
                                <img src="/generated/image-technical-support-specialist-with-headse-1765484929745-3.webp" alt="Support specialist" class="w-full h-full object-cover" />
                            </div>
                            <div class="text-xs font-mono text-gray-500 uppercase tracking-wider mb-2 flex items-center gap-2">
                                <div class="status-light status-light-amber"></div>
                                Technical Guide
                            </div>
                            <h3 class="text-2xl font-bold text-gray-900 group-hover:text-gray-600 transition-colors">Why generic WordPress hosting fails for LMS sites</h3>
                        </div>
                    </div>
                </div>


    </main>

    <Footer />
</div>

