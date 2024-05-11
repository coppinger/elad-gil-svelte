<script>
	export let title;
</script>

<div class="inline-flex gap-2">
	<p class="inline">
		<span class="font-bold">{title} </span>
		<slot></slot>
	</p>
</div>
