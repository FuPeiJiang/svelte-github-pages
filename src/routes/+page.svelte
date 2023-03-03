<script>
    import { goto } from '$app/navigation';

    function handleClick(event) {
        goto('/hello')
    }
</script>

<button on:click={handleClick}>hello1</button>