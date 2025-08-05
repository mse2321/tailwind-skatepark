<button class="text-white px-3 py-1.5 rounded-md shadow-sm hover:bg-blue-500 bg-teal-500 border-2">Button</button>

<script>
  const { label = 'Button', ...props } = $props();
</script>

<button {...props}>{label}</button>