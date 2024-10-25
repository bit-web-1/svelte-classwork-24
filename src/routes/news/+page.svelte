<script>
    export let data;
    const posts = data.posts; //This holds my array of posts
</script>

<h2>News about learning SvelteKit</h2>

{#each posts as post}
    <p>{post.body}</p>
{/each}