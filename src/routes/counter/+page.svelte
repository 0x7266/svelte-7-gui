<script lang="ts">
  let counter = $state(0)
  function decrement() {
    counter--
  }
  function increment() {
    counter++
  }
</script>

<div class="flex flex-col gap-2 bg-zinc-700 p-4 rounded-lg border h-fit text-2xl text-zinc-300">
  <input type="number" disabled value={counter} class="rounded-lg px-2 py-1 text-center"/>
  <div class="flex gap-2 w-full">
    <button aria-labelledby="decrement" class="w-full bg-zinc-400 p-2 border border-zinc-600 rounded-lg hover:bg-rose-400 hover:text-zinc-100" onclick={decrement}>
      -
    </button>
    <button aria-labelledby="increment" class="w-full bg-zinc-400 p-2 border border-zinc-600 rounded-lg hover:bg-emerald-400 hover:text-zinc-100" onclick={increment}>
      +
    </button>
  </div>
</div>
