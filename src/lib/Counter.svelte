<script>
 import Button from "./Button.svelte";
 import Header from "./Header.svelte";
 
 import {count} from "./store"
</script>

<main>
  <Header username="Batool"></Header>
  <Button text="Count is"></Button>
  <h1>{$count}</h1>
</main>