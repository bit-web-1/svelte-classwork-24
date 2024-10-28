<script>
    let count = 0;

    function incrementCount() {
        count++;
    }
</script>

<button on:click={incrementCount}>Add one</button>
<p>The number of clicks is: {count}</p>