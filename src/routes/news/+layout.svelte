<div>
  <aside>
    <p>This is an aside only on the news page</p>
    <a href="/news/article">Article</a>
  </aside>
  <main>
    <slot />
  </main>
</div>

<style>
  div {
    display: flex;
  }
  aside {
    background-color: #eee;
    padding: 1em;
    margin-right: 1em;
  }
</style>
