<script>
  export let state = 'primary';

  const buttonStyles = {
    primary: 'bg-blue-500 hover:bg-blue-700 text-white',
    disabled: 'bg-gray-300 text-gray-500 cursor-not-allowed',
    error: 'bg-red-500 hover:bg-red-700 text-white',
    success: 'bg-green-500 hover:bg-green-700 text-white'
  };
</script>

<button
  class="py-2 px-4 rounded focus:outline-none
    {buttonStyles[state]}"
  disabled={state === 'disabled'}
>
  <slot>Button</slot>
</button>