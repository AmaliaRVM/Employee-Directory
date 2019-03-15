<template>
    <div class="employeepage">
        <SecondHeader/>
        <Profile/>

    </div>
</template>

<script>
import SecondHeader from './SecondHeader.vue'
import Profile from './Profile.vue'

export default {
components: {
    SecondHeader,
    Profile,
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
