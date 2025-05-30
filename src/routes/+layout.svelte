<script>
  import "../style.css";
  const { children } = $props();

</script>

<div class="flex w-screen justify-center p-2">
<div class="flex max-w-4xl">

  {@render children()}
</div>
</div>
