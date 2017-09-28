<template>
    <div>
        <button @click="increment">증가</button>
        <button @click="decrement">감소</button>
    </div>
</template>

<script>
    export default {
        name: 'Counter',
        data () {
            return {}
        },
        methods: {
            increment () {
                this.$store.commit('INCREMENT')
            },
            decrement () {
                this.$store.commit('DECREMENT')
            }

        }
    }
</script>

<style>

</style>