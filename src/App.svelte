<script>
  import Test1 from './components/Test1.svelte';
  import Test2 from './components/Test2.svelte';
</script>

<svelte:head>
  <title>Svelte + Sveasy + Windicss</title>
</svelte:head>

<Test1 padding="medium" />
<Test2 padding="small" class="border-2 border-black" />
