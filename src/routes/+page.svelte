<script>
    import { goto } from '$app/navigation'
    import { base } from '$app/paths'

    function handleClick(event) {
        goto(`${base}/hello`)
    }
</script>

<button on:click={handleClick}>hello1</button>
<a href="{base}/hello">hello</a>