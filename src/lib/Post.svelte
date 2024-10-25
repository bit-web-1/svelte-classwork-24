<script>
    export let post; // Takes in a post object as a prop
</script>

<article>
    <h3>{post.title}</h3>
    <p>{post.body}</p>
</article>

<style>
    article {
        background-color: #dee;
        padding: 0.5em;
        margin-bottom: 1em;
    }
</style>