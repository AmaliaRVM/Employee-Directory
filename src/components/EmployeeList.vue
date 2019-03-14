<template>
    <div id="employeelist">
        <EmployeeListItem v-for="(element, index) in employees" :key="index" v-bind:list='element'></EmployeeListItem>
    </div>
</template>

<script>
import EmployeeListItem from './EmployeeListItem.vue'

export default {
    data() {
        return {
            employees: [
                "People1",
                "People2",
                "People3",
                "People4",
                "People5",
                "People6",
                "People7",
                "People8" 
            ]
        }
    },

    components: {
        EmployeeListItem,

    }

}
</script>

<style>

</style>
