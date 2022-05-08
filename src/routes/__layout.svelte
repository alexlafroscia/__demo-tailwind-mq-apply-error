<script>
  import "../app.css";
</script>

<slot />

<style lang="postcss">
  @media (prefers-color-scheme: dark) {
    :global(body) {
      @apply bg-gray-900;
    }
  }
</style>
