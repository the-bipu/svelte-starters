<script lang="ts">
  import { theme } from "../stores/theme";
  import welcome from '$lib/images/svelte-welcome.png';

  function toggleTheme() {
    theme.update((current) => (current === "light" ? "dark" : "light"));
  }
</script>

<svelte:head>
  <title>Home</title>
  <meta name="description" content="Svelte demo app" />
</svelte:head>

<section class="flex-1 flex flex-col justify-center items-center w-full">
  <img src={welcome} alt="" />
  <div>demo application of svelte kit;</div>
</section>
