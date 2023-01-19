<script>
export default {
    name: "AppTitle",
    data() {
        return {
            title: "La mia prima app con Vite!"
        }
    }
}
</script>

<template>
    <h1>{{ title }}</h1>
</template> 

<style scoped>
h1 {
    color: darkred;
    font-size: 80px;
    margin: 20px
}
</style>