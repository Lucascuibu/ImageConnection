<script lang="ts">
	let count = 0;

	function handleClick() {
		count += 1;
	}
	import { Button } from '$lib/components/ui/button';
	import { getLocalTimeZone, today } from '@internationalized/date';
	import { Calendar } from '$lib/components/ui/calendar/index.js';

	let value = today(getLocalTimeZone());
</script>

<!-- <h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<button on:click={handleClick}>
	Cliced {count}
	{count === 1 ? 'time' : 'times'}
</button>

<h1 class="text-3xl font-bold underline bg-slate-400">Hello world!</h1>


 
<Button>Click me</Button>
<Calendar bind:value class="rounded-md border" /> -->

<div class="s-screen pt-8 h-screen px-8">
  <div class="justify-between flex items-end border-b pb-1">
    <h1 class="text-4xl font-medium">ImageConnection</h1>
    <p>Cur:89 pics</p>
  </div>
	
</div>
