<script>
  export let post; // Takes in a post object as a prop
  let isAlert = post.id > 3 ? true : false; // Ternary operator (short if statement)
</script>

<!-- Apply the alert class if the id is over 3 -->
<article class:alert={isAlert}>
  <h3>{post.title}</h3>
  <p>{post.body}</p>
</article>

<style>
  article {
    background-color: #dee;
    padding: 0.5em;
    margin-bottom: 1em;
  }
  .alert {
    background-color: coral;
  }
</style>
