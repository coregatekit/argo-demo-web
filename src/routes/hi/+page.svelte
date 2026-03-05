<script lang="ts">
  import { resolve } from '$app/paths';
</script>

<svelte:head>
  <title>Hi</title>
  <meta name="description" content="Hi page" />
</svelte:head>

<div class="text-column">
  <h1>Hi there!</h1>

  <p>
    This is the hi page. You can navigate to the <a href={resolve('/about')}>about page</a> to learn more about this app.
  </p>
</div>