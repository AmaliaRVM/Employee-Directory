<template>
    <div class="employeepage">
        <SecondHeader/>

    </div>
</template>

<script>
import SecondHeader from './SecondHeader.vue'

export default {
components: {
    SecondHeader,
}
}
</script>

<style scoped>
.employeepage {
    width: 40vw;
    height: 90vh;
    margin: 20px;
    border:solid brown;
}

</style>
