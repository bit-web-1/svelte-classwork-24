<script>
    export let data;
    const posts = data.posts; //This holds my array of posts
</script>

<h2>News about learning SvelteKit</h2>

{#each posts as post}
<article>
    <h3>{post.title}</h3>
    <p>{post.body}</p>
</article>
{/each}

<style>
    article {
        background-color: #dee;
        padding: 0.5em;
        margin-bottom: 1em;
    }
</style>