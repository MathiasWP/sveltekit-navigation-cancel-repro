<script>
    import { beforeNavigate } from '$app/navigation';

    beforeNavigate((navigation) => {
        navigation.cancel()
    })
</script>

<a href="/other">Cancel navigation</a>
