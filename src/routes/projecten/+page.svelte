<script>
    export let data
    import Projecten from "../../lib/organisms/Projecten.svelte"
</script>

<main>
    <Projecten {data} />
</main>

<style>
    main {
        margin-top: 2rem;
    }
</style>