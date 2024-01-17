<script>
/*
    metodologia:
    1)importazione componente;
    2)dichiarazione del componente all'interno dell'oggetto
    3)utilizzo del componente
*/
//1) importazione
import AppHeader from './components/AppHeader.vue';

export default {
    data() {
        return { count: 0 }
    },
    //2) Dichiarazione dei componenti
    components: {
        AppHeader
    }
};
</script>

<template>
    <div>
        <!--3)utilizzo del componente-->
        <AppHeader/>
        <h1>
            Ciao ragazzi
        </h1>
        <p>
            {{ count }}
        </p>
        <button @click="count++">
            Incrementa count
        </button>
    </div>
</template>

<style scoped>

</style>
