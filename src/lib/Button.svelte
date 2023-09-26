<script>
// @ts-nocheck

    export let text;

    import {count} from "./store"

    const increment = () => {
    $count += 1
  }
</script>


<button on:click={increment}>
    {text} {$count}
  </button>
  