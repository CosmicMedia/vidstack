<script>
  import MetaTags from '$lib/components/base/MetaTags.svelte';
  import MainLayout from '$lib/layouts/MainLayout.svelte';
  import Footer from '$lib/layouts/Footer.svelte';

  import HeroSection from './HeroSection.svelte';
  import FeaturesSection from './FeaturesSection.svelte';
  import CommunitySection from './CommunitySection.svelte';
</script>

<MetaTags
  title="Vidstack: Where people build awesome media experiences"
  description="Vidstack makes it easier to work with video & audio on the web."
/>

<MainLayout --navbar-border-bottom="none" --main-padding-x="none" --main-overflow-x="hidden">
  <HeroSection />
  <FeaturesSection />
  <CommunitySection />
  <Footer slot="after-main" />
</MainLayout>
