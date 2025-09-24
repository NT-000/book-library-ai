<script lang="ts">
    import {Button} from "$components"
    import picture from "$assets/book_magnify.png"
</script>


<section class="default-margin hero">
    <div class="hero-text">
        <h1>BookFinder</h1>
        <h3>Your library.</h3>
        <h4 class="mt-l">
            Keep track and find books you own.
        </h4>
        <h4 class="mb-s">
            This app simplifies managing your book collection.
        </h4>
        <Button href="/register">Sign Up</Button>
    </div>
    <img src="{picture}" alt="" class="hero-image">
</section>

<style>
    .hero {
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin-top: 100px;
        margin-bottom: 80px;

    }

    .hero-image {
        width: 40%
    }

    .hero-text {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        width: 55%;
        padding-right: 40px;
    }
</style>