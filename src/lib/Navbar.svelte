<script lang="ts">
    import { AppBar } from "@skeletonlabs/skeleton";

    const openArtStation = () => {
        window.open("https://www.artstation.com/tristanvoulelis", "_blank");
    };

    const navs = [
        {
            "name": "Home",
            "link": "/"
        },
        {
            "name": "Gallery",
            "link": "/gallery"
        },
        {
            "name": "About",
            "link": "/about"
        }
    ]

</script>

<AppBar gridColumns="grid-cols-1" slotDefault="place-self-center">
	<!-- <svelte:fragment slot="lead">
        <img src="src/assets/tristan.jpg" alt="Tristan logo" class="logo"/>
    </svelte:fragment> -->
    {#each navs as nav}
        <button class="btn btn-primary" on:click={openArtStation}>{nav.name}</button>
    {/each}
</AppBar>
<div class="w-full h-12" />

<style>
    .logo {
        width: 3em;
    }
</style>