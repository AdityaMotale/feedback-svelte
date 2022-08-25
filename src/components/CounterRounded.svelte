<script lang="ts">
  let count: number = 0;

  const incr = () => {
    count += 1;
  };
</script>

<div class="rounded-full bg-purple-900 h-28 w-28" on:click={incr}> 
    {count}
</div>
