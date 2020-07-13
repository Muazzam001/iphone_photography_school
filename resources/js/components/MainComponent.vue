<template>
    <div class="container">

        <div class="container__wrapper">
            <post-component></post-component>
        </div>

    </div>
</template>

<script>
    import PostComponent from './partials/PostComponent';

    export default {
        name: "MainComponent",
        components: {
            PostComponent,
        },
        mounted() {
            console.log('Main Component mounted.')
        }
    }
</script>
