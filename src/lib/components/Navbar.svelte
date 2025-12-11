<script>
    import { onMount } from 'svelte';

    let isScrolled = false;

    onMount(() => {
        const handleScroll = () => {
            isScrolled = window.scrollY > 20;
        };
        window.addEventListener('scroll', handleScroll);
        return () => window.removeEventListener('scroll', handleScroll);
    });
</script>

<nav class="fixed top-0 left-0 right-0 z-50 transition-all duration-300 {isScrolled ? 'control-panel py-3' : 'bg-transparent py-4'} border-b-2 {isScrolled ? 'border-[var(--color-metal)]' : 'border-transparent'}">
    <div class="container mx-auto px-6 flex items-center justify-between">
        <!-- Logo -->
        <a href="/" class="flex items-center gap-3 text-white font-mono text-lg tracking-wider">
            <svg width="24" height="31" viewBox="0 0 90 115" fill="none" xmlns="http://www.w3.org/2000/svg">
                <path fill-rule="evenodd" clip-rule="evenodd" d="M31.8701 9.95388L15.3109 19.4791L31.8819 29.0064L48.446 19.4812L31.8701 9.95388ZM53.2588 27.7795L36.6927 37.3058L36.6911 56.3603L53.2588 46.8319V27.7795ZM58.0696 55.1313L41.5014 64.66L58.072 74.187L74.6383 64.6605L58.0696 55.1313ZM79.4486 72.9601L62.883 82.4862V101.538L79.4486 92.0122V72.9601ZM53.2614 101.539V82.4864L36.6903 72.9591V92.012L53.2614 101.539ZM27.0694 56.3613L10.5003 46.8319V27.7788L27.0711 37.3058L27.0694 56.3613ZM27.0687 67.4269L4.48643 54.4394C2.25391 53.1554 0.878662 50.7828 0.878662 48.215V19.4801C0.878662 17.7684 1.79538 16.1867 3.28356 15.3307L28.2608 0.963381C30.4933 -0.320696 33.2439 -0.321154 35.4766 0.962171L60.474 15.3299C61.963 16.1857 62.8804 17.7679 62.8804 19.4801V46.8319L86.665 60.5111C88.1535 61.3671 89.0702 62.9489 89.0702 64.6607V93.3956C89.0702 95.9635 87.6948 98.3361 85.4621 99.62L60.4776 113.988C58.9894 114.843 57.1558 114.843 55.6673 113.988L30.6773 99.6202C28.4444 98.3365 27.0687 95.9635 27.0687 93.3954V67.4269Z" fill="var(--color-crt-green)"/>
            </svg>
            <span class="crt-text">TangibleXP</span>
        </a>

        <!-- Links -->
        <div class="hidden md:flex items-center gap-6 text-xs font-mono uppercase tracking-wider text-gray-400">
            <a href="#" class="hover:text-[var(--color-crt-green)] transition-colors flex items-center gap-1">
                <div class="w-1.5 h-1.5 bg-[var(--color-crt-green-dim)]"></div>
                Hosting
            </a>
            <a href="#" class="hover:text-[var(--color-crt-green)] transition-colors flex items-center gap-1">
                <div class="w-1.5 h-1.5 bg-[var(--color-crt-green-dim)]"></div>
                Plugins
            </a>
            <a href="#" class="hover:text-[var(--color-crt-green)] transition-colors flex items-center gap-1">
                <div class="w-1.5 h-1.5 bg-[var(--color-crt-green-dim)]"></div>
                Agency
            </a>
            <a href="#" class="hover:text-[var(--color-crt-green)] transition-colors flex items-center gap-1">
                <div class="w-1.5 h-1.5 bg-[var(--color-crt-green-dim)]"></div>
                Resources
            </a>
            <a href="#" class="hover:text-[var(--color-crt-green)] transition-colors flex items-center gap-1">
                <div class="w-1.5 h-1.5 bg-[var(--color-crt-green-dim)]"></div>
                About
            </a>
        </div>

        <!-- CTA -->
        <div class="hidden md:flex items-center gap-3">
            <div class="status-light status-light-green"></div>
            <a href="#" class="text-xs font-mono uppercase tracking-wider text-[var(--color-crt-green)] hover:text-[var(--color-crt-amber)] transition-colors flex items-center gap-2">
                Get Started
                <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                    <path d="M5 12h14M12 5l7 7-7 7"/>
                </svg>
            </a>
        </div>
        
        <!-- Mobile Menu Button -->
        <button class="md:hidden bevel-inset bg-[var(--color-panel-dark)] p-2">
            <svg width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="var(--color-crt-green)" stroke-width="2" stroke-linecap="square" stroke-linejoin="miter">
                <line x1="3" y1="12" x2="21" y2="12"></line>
                <line x1="3" y1="6" x2="21" y2="6"></line>
                <line x1="3" y1="18" x2="21" y2="18"></line>
            </svg>
        </button>
    </div>
</nav>
