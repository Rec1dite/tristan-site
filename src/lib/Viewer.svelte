<script>
    export let content = "";
</script>

{#if content !== ""}
<div class="w-full h-full">
    asdf
</div>
{/if}

<style>
    div {
        position: absolute;
        z-index: 100;
        border: 1px solid red;
    }
</style>