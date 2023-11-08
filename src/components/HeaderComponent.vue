<template>
    <header>
        <h2>
            {{ titolo }}
        </h2>
    </header>
</template>

<script>
    export default {
        name: 'HeaderComponent',
        data(){
            return {
                titolo: 'sono un header :)'
            }
        }
    }
</script>

<style lang="css" scoped>

h2 {
    color: red;
}

</style>