<script>
	let y = $state(0);
</script>

<svelte:window bind:scrollY={y} />

<div class="mt-20 min-h-[200vh]">
	<div class="animate-enter" style="--stagger: 1">
		<h1 class="text-center font-serif text-9xl font-bold">
			<span>Qualcosa</span><br />
			<span
				class="bg-gradient-to-r from-rose via-iris to-foam bg-clip-text text-transparent"
				>di bello</span
			>
		</h1>
	</div>
</div>
