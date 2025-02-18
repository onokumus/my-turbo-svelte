<script lang="ts">
  let count = 0;

  function handleClick() {
    count += 1;
  }
</script>

<button class="border-2 border-teal-400 p-3 cursor-pointer bg-teal-300 rounded m-4" onclick={handleClick}>
  clicks: {count}
</button>
