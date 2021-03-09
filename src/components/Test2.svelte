<script>
  export let padding;
  let className;
  export { className as class };
</script>

<div
  class="bg-red-300 {padding === 'small' ? 'px-2 py-3' : ''} {padding ===
  'medium'
    ? 'px-5 py-6'
    : ''} {className || ''}"
>
  Test 2
</div>
