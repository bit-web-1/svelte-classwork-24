<script>
    export let data;
    const posts = data.posts; //This holds my array of posts
    import Post from "$lib/Post.svelte";
</script>

<h2>News about learning SvelteKit</h2>

{#each posts as post}
    <Post {post} />
{/each}

<style>
    
</style>