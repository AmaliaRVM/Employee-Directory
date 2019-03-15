<template>
    <div id="employeelist">
        <EmployeeListItem v-for="(element, index) in employees" :key="index" v-bind:employee='element'></EmployeeListItem>
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

    components: {
        EmployeeListItem,

    }

}
</script>

<style>

</style>
