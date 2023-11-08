<template>
    <!--qui va html del componente-->
    <HeaderComponent/>
    <main>
        <h2>
            {{titolo}}
        </h2>
    </main>
</template>

<script>
    import HeaderComponent from  './components/HeaderComponent.vue'
    export default {
        name:'App',
        components: {
            HeaderComponent
        },
        data(){
           return {
            titolo: 'ciaooo!!',

           }
        },
        methods: {

        }
    }
</script>

<style lang="css">

main {
    text-align: center;
}

</style>