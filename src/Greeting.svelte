<script>
    export let first_name
    export let last_name
    $: name = first_name + ' ' + last_name
</script>
<style>
  h1 {
    color: blue;
  }
</style>

<h1>Hello {name}!!</h1>
