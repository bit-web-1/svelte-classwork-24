<script>
  export let post; // Takes in a post object as a prop
  let isAlert = true;
  if (post.id > 4){isAlert=false}
</script>


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
