<template>
    <div class="search">
        <h3>{{searchBar}}</h3>
        <input type="text" placeholder="Search.." name="search2">
        <button type="submit"></button> 
    </div>
</template>

<script>
export default {
    data() {
        return {
            searchBar: "Search bar"
        }
    }

}
</script>

<style scoped>
.search {
    border: 2px solid green;
    margin:10px;
}

</style>
