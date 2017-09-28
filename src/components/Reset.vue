<template>
    <div>
        <button @click="reset">리셋</button>
    </div>
</template>

<script>
    export default {
        name: 'Reset',
        data () {
            return {}
        },
        methods: {
            reset () {
                this.$store.commit('RESET')
            }
        }
    }
</script>

<style>

</style>