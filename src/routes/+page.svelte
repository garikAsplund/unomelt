<script lang='ts'>
    let green: boolean = false;
</script>

<h1 class:text-green-300={green}>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
<button class="btn text-xl hover:text-purple-400" on:click={() => {console.log(green); green = !green}}>Click me to see magic happen</button>
<textarea class="text-red-300 mb-4 border-cyan border-10"></textarea>
<div class="flex w-screen h-32 m-3 justify-center text-5xl bg-blue-500a">aeu</div>
