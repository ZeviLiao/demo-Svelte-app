<script>
  import Greeting from "./Greeting.svelte";
  export let name;
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<Greeting/>
