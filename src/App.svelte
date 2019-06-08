<script>
  import Greeting from "./Greeting.svelte";
  import LogIn from "./LogIn.svelte";
  import FrameworkList from "./FrameworkList.svelte";
  import EventDemo from "./EventDemo.svelte";
  import BindingDemo from "./BindingDemo.svelte";
  export let name;
</script>

<style>
  h1 {
    color: purple;
  }
</style>

<h1>Hello {name}!</h1>
<Greeting first_name="Zevi" last_name="Liao" />
<LogIn />
<FrameworkList />
<EventDemo/>
<BindingDemo/>