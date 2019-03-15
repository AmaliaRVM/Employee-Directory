<template>
    <div class="homepage">
        <Header/>
        <SearchBar/>
        <EmployeeList :getInfo="getInfo"/>
    </div>
</template>

<script>
import Header from './Header.vue'
import SearchBar from './SearchBar.vue'
import EmployeeList from './EmployeeList.vue'

export default {
    components: {
        Header,
        SearchBar,
        EmployeeList,
    },

    props: {
        appInfo: Function
    },

    methods: {
        getInfo(x) {
            this.appInfo(x)
        }
    }

}
</script>

<style scoped>
.homepage{
    width: 40vw;
    height: 90vh;
    margin: 20px;
    border:solid orange;
}
</style>
