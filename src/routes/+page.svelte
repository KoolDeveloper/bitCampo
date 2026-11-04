<script>
	import {resolve} from '$app/paths';
</script>

<div class="bg-bg text-fg flex min-h-screen flex-col items-center justify-center">
	<h1>Welcome to BitCampo</h1>
	<p class="animate-pulse">Press Start to begin your journey.</p>
	<a href={resolve('/application')}><button class="nes-btn is-primary animate-pulse">Start</button></a>
</div>
