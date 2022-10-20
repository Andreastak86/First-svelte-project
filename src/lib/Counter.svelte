<script>
  let count = 0
  const increment = () => {
    count += 7
  }
  const decrement = () => {
    count -= 7
  }
</script>

<button name="increace" on:click={increment}>
  count is {count}
</button>
<button name="decrease" on:click={decrement}>
  count is {count}
</button>

<style>
  button {
    background: yellow;
    border-radius: 20px;
    padding: 1rem;
  }
  button:hover {
    background: blue;
  }
</style>