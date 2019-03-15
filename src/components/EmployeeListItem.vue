<template>
    <div id="listItem">
        <ul>
            <li v-for="(element,index) in employee" :key="index">
                {{element}}
            </li>
        </ul>
    </div>
</template>

<script>
export default {
    props: {
        employee: Object
        
    }
}
</script>

<style scoped>
#listItem {
    border: 2px solid red;
    margin:10px;  
}
</style>

