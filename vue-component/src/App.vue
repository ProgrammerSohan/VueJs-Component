<template>
    <div>

        <CompOne />
        <UserInfo />
    </div>

</template>
<script>
import CompOne from './components/CompOne.vue';
import UserInfo from './components/UserInfo.vue';

export default{
    name: 'App',
    components: {
        CompOne,
        UserInfo

    }

}


</script>
<style>

</style>