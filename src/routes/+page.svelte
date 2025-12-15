<script>
    import Navbar from '$lib/components/Navbar.svelte';
    import Hero from '$lib/components/Hero.svelte';
    import FeatureGrid from '$lib/components/FeatureGrid.svelte';
    import Testimonial from '$lib/components/Testimonial.svelte';
    import Timeline from '$lib/components/Timeline.svelte';
    import DarkFeatures from '$lib/components/DarkFeatures.svelte';
    import EnterpriseGrid from '$lib/components/EnterpriseGrid.svelte';
    import CustomerStories from '$lib/components/CustomerStories.svelte';
    import FooterCTA from '$lib/components/FooterCTA.svelte';
    import Footer from '$lib/components/Footer.svelte';
</script>

<Navbar />
<main>
    <Hero />
    <FeatureGrid />
    <Testimonial />
    <Timeline />
    <DarkFeatures />
    <EnterpriseGrid />
    <CustomerStories />
    <FooterCTA />
</main>
<Footer />

