<script lang="ts">
	import '../app.css';
	let { children } = $props();
</script>

<main class="h-dvh flex gap-2 bg-zinc-900">
<aside class="h-full bg-zinc-800 border-r-2 border-r-zinc-700 flex flex-col gap-2 p-6 font-semibold font-mono text-xl text-zinc-300">
  <a class="hover:text-zinc-50" aria-label="counter" href="/counter">Counter</a>
  <a class="hover:text-zinc-50" aria-label="temperature converter" href="/temperatureconverter">Temperature converter</a>
  <a class="hover:text-zinc-50" aria-label="flight booker" href="/flight booker">Flight booker</a>
  <a class="hover:text-zinc-50" aria-label="timer" href="/timer">Timer</a>
  <a class="hover:text-zinc-50" aria-label="crud" href="/crud">CRUD</a>
  <a class="hover:text-zinc-50" aria-label="circle drawer" href="/circledrawer">Circle drawer</a>
  <a class="hover:text-zinc-50" aria-label="cells" href="/cells">Cells</a>
</aside>
{@render children()}
</main>
