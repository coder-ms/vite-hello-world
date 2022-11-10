
<template>
    <header>
        <h1> {{ message0 }} </h1>
    </header>
    <footer>
        Made by {{ message1 }}
    </footer>
</template>

import HeaderComponent from './components/HeaderComponent.vue';
<script>
export default {
    data() {
        return {
            message0: 'Hello world !',
            message1: 'Mike'
        }
    },
    methods: {

    },
}
</script>



<style lang="css">
header {
    width: 100%;
    height: 70px;
    padding: 20px;
    background-color: black;
}

h1 {
    color: red;
}
</style>
