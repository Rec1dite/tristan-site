<script lang="ts">
    import Navbar from "./Navbar.svelte";
    import Banner from "./Banner.svelte";
    import Gallery from "./Gallery.svelte";
    import Bio from "./Bio.svelte";
  import { AppShell } from "@skeletonlabs/skeleton";
</script>

<AppShell regionPage="relative" slotPageHeader="fixed top-0 z-10 w-full">
	<svelte:fragment slot="pageHeader">
  <Navbar />
  </svelte:fragment>

  <br /><br /><br />
  <Banner />
  <br />
  <Bio />
  <br />
  <Gallery />

	<svelte:fragment slot="pageFooter">
  </svelte:fragment>
</AppShell>