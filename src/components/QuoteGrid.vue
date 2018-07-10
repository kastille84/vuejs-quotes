<template>
    <div class="row">
        <app-quote v-for="quote in quotes" :key="quote"></app-quote>
    </div>
</template>

<script>
    import Quote from './Quote.vue';

    export default {
        props: ['quotes'],
        data: function() {
            return {

            }
        },
        components: {
            appQuote: Quote
        }
    }
</script>

<style>

</style>

