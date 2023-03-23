<script>
export default {
    data() {
        return {
            clickNum: 0,
        }
    },

    methods: {
        clickTitle() {
            this.clickNum += 1;
        }
    }
}
</script>

<template>
    <h1 @click="clickTitle()">La mia prima app con Vite</h1>

    <p v-if="clickNum < 1">Prova a cliccare il titolo.</p>
    <p v-else-if="clickNum < 10">hai cliccato <span>{{ clickNum }}</span> volte</p>
    <p v-else>ok basta.</p>
</template>

<style scoped>
h1 {
    text-align: center;
    padding: .6em;
}

p {
    text-align: center;
    color: white;
}

p>span {
    font-size: 1.2em;
    font-weight: bolder;
    color: green;
}
</style>
