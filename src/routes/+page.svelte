<script lang="ts">
  import Navbar from "$lib/components/Navbar.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import LogoStrip from "$lib/components/LogoStrip.svelte";
  import ProductGrid from "$lib/components/ProductGrid.svelte";
  import Testimonials from "$lib/components/Testimonials.svelte";
  import Timeline from "$lib/components/Timeline.svelte";
  import FeatureDark from "$lib/components/FeatureDark.svelte";
  import BenefitsGrid from "$lib/components/BenefitsGrid.svelte";
  import CustomerStories from "$lib/components/CustomerStories.svelte";
  import Awards from "$lib/components/Awards.svelte";
  import BottomCTA from "$lib/components/BottomCTA.svelte";
  import Footer from "$lib/components/Footer.svelte";
  import StickyBanner from "$lib/components/StickyBanner.svelte";
</script>

<Navbar />

<main>
  <Hero />
  <LogoStrip />
  <ProductGrid />
  <Testimonials />
  <Timeline />
  <FeatureDark />
  <BenefitsGrid />
  <CustomerStories />
  <Awards />
  <BottomCTA />
</main>

<Footer />
<StickyBanner />

