<template>
<div>
    <ul v-if="errors">
        <li :key="errorItem" v-for="errorItem in errors">{{errorItem}}</li>
    </ul>
</div>
</template>

<script>
export default {
    name: "Errors",
    props: ['errors']
}
</script>

<style scoped>

</style>
