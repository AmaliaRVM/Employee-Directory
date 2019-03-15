<template>
    <div id="listItem" @click="handleClick">
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
        employee: Object,
        itemInfo:Function
        
    },

    methods: {
        handleClick(){
            this.itemInfo(this.employee)
        }
    }
}
</script>

<style scoped>
#listItem {
    border: 2px solid red;
    margin:10px;  
}
</style>

