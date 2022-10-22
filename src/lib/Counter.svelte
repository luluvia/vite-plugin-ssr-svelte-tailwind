<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button class="bg-gray-100 dark:bg-gray-900 border px-4 py-2 transition-colors rounded-lg cursor-pointer hover:border-blue-500"
        on:click={increment}>
  count is {count}
</button>
