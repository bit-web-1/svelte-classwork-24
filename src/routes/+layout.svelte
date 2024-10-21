<script>
    import Navigation from "$lib/Navigation.svelte"
</script>

<h1>I'm Learning SvelteKit</h1>

<Navigation />

<slot />

<footer>This should be on every page because it's in the layout file</footer>

<style>
    :global(*) {
        font-family: system-ui, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
    }
    footer {
        padding: 1em;
        background-color: #aaa;
        margin-top: 1em;
    }
</style>