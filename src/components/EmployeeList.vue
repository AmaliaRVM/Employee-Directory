<template>
    <div id="employeelist">
        <EmployeeListItem 
        :itemInfo="itemInfo"
        v-for="(element, index) in employees" 
        :key="index" 
        v-bind:employee='element'>
        </EmployeeListItem>
    </div>
</template>

<script>
import EmployeeListItem from './EmployeeListItem.vue'
import employeeslist from '../Data/data.json'

export default {
    data() {
        return {
            employees: employeeslist
        }
    },

    props: {
        getInfo: Function
    },

    components: {
        EmployeeListItem,

    },

    methods: {
        itemInfo(info){
            this.getInfo(info)
        },

        
    
    
        
        
    }

}
</script>

<style>

</style>
