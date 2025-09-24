<script lang="ts">
    const {children} = $props()
</script>

<div class="pulse">
    {@render children()}
</div>

<style>
    @keyframes pulse {
        0% {
            transform: scale(1);
        }
        50% {
            transform: scale(1.05);
        }
        100% {
            transform: scale(1);
        }
    }

    .pulse {
        animation: pulse 2s ease-in-out infinite alternate;
        transform-origin: center;
        display: inline-block;
    }

</style>