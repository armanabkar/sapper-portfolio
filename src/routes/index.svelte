<script>
  import { Information } from "../information.config";
</script>

<svelte:head>
  <title>{Information.name}</title>
</svelte:head>

<div class="container">
  {#each Information.about as info}
    <p>
      {@html info}
    </p>
  {/each}
</div>

<style>
</style>
