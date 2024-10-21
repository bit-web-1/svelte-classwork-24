<script>
    import Navigation from "$lib/Navigation.svelte"
</script>

<Navigation />

<slot />

<footer>This should be on every page because it's in the layout file</footer>

<style>
    footer {
        padding: 1em;
        background-color: #aaa;
        margin-top: 1em;
    }
</style>