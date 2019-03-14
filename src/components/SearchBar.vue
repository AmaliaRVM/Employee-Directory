<template>
    <div class="search">
        <h3>{{searchBar}}</h3>
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
