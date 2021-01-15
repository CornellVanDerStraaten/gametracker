<template>
    <div>
        <div v-bind:key="toplay.id" v-for="toplay in toplays">
            <h3>{{toplay.title}}</h3>
        </div>
    </div>
</template>

<script>
    export default {
        name: "Toplays",
        props: ["toplays"]
    }
</script>

<style scoped>

</style>