<script>
	import Navigation from "../components/Navigation.svelte";

</script>
<div class="main-container">
    <Navigation />

    <slot></slot>
</div>

<style lang="scss">
    .main-container {
        padding: 1rem;
    }
</style>