<script>
  import Nav from '$lib/Nav.svelte'
</script>

<div class="blog">
  <Nav></Nav>
  <slot />
</div>

<style>
  .blog {
    height : 100vh;
    background: rgb(219, 171, 163);
  }
</style>