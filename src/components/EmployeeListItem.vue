<template>
    <div id="listItem">
        {{list}}
    </div>
</template>

<script>
export default {
    props: {
        list: String
    }
}
</script>

<style scoped>
#listItem {
    border: 2px solid red;
    margin:10px;  
}
</style>

