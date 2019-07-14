<script>
	import { onMount } from 'svelte';

    export let margin = '--s0';

    $: id = margin

	onMount(() => {
		document.querySelectorAll(`.stack${id} > * + *`).forEach(e => e.style.marginTop = `var(${margin}, 1rem)`);
	});
</script>

<div class={`stack${id}`}>
    <slot>
    </slot>
</div>