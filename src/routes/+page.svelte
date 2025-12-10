<script>
  import Navbar from '$lib/components/Navbar.svelte';
  import Hero from '$lib/components/Hero.svelte';
  import Logos from '$lib/components/Logos.svelte';
  import WhyNevis from '$lib/components/WhyNevis.svelte';
  import Products from '$lib/components/Products.svelte';
  import Stats from '$lib/components/Stats.svelte';
  import Testimonials from '$lib/components/Testimonials.svelte';
  import Founders from '$lib/components/Founders.svelte';
  import FAQ from '$lib/components/FAQ.svelte';
  import BottomCTA from '$lib/components/BottomCTA.svelte';
  import Footer from '$lib/components/Footer.svelte';
</script>

<div class="min-h-screen bg-[#f5f5f5] font-sans selection:bg-black selection:text-white">
  <Navbar />
  <Hero />
  <Logos />
  <WhyNevis />
  <Products />
  <Stats />
  <Testimonials />
  <Founders />
  <FAQ />
  <BottomCTA />
  <Footer />
</div>

