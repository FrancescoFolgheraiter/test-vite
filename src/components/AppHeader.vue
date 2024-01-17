<script>
export default {
    data() {
        return { 
            title:"Ciao ragazzi"
        }
    },
};
</script>

<template>
    <div>
        <header>
            <h1 class="main-title">
                {{ title }}
            </h1>
        </header>
    </div>
</template>

<style scoped>
    header{
        padding:20px;
        background-color: aquamarine;
    }
</style>
