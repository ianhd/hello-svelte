<script>
  let counter = 1
  const btnClick = () => {
    counter += 1
  }
</script>

<div class="w-full h-full grid items-center">
  <div class="font-bold">
    hello {counter}
    <button class="btn btn-primary" on:click={btnClick}>button here</button>
  </div>
</div>
