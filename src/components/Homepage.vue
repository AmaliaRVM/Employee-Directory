<template>
    <div class="homepage">
        <Header/>
        <SearchBar/>
        <EmployeeList/>
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
