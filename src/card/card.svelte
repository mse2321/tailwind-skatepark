<script>
  const { title = 'Card Title', description = '' } = $props();
</script>

<div class="rounded-md bg-slate-50 p-4 shadow-md hover:shadow-sm transition-shadow duration-200">
  <h2 class="font-semibold text-lg">{title}</h2>
  <p class="mt-1">{description}</p>
</div>
