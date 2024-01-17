<script>
export default {
    data() {
        return {
            title: 'La mia prima app con Vite!'
         }
    },
    template: `<div>count is {{ count }}</div>`,
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

header {
    padding: 20px;
    background-color: aquamarine;
}
.main-title {
    color: green;
    text-align: center;   
}

</style>
