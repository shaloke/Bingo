<script>
  import { Button } from 'attractions';
  let count = 0
  const increment = () => {
    count += 1
  }
</script>

<Button on:click={increment}>
  Clicks: {count}
</Button>

<style>
  Button {
    font-family: inherit;
    font-size: inherit;
    padding: 1em 2em;
    color: #ff3e00;
    background-color: rgba(255, 62, 0, 0.1);
    border-radius: 2em;
    border: 2px solid rgba(255, 62, 0, 0);
    outline: none;
    width: 200px;
    font-variant-numeric: tabular-nums;
    cursor: pointer;
  }

  Button:focus {
    border: 2px solid #ff3e00;
  }

  Button:active {
    background-color: rgba(255, 62, 0, 0.2);
  }
</style>
