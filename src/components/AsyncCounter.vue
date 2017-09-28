<template>
    <div>
        <button @click="asyncCounter">비동기 증가</button>
    </div>
</template>

<script>
    export default {
        name: 'AsyncCounter',
        data (){
            return {}
        },
        methods: {
            asyncCounter () {
                this.$store.dispatch('asyncIncrement')
            }
        }
    }
</script>

<style>

</style>