<template>
    <div>

        <CompOne />
        <UserInfo />
        <Title />
    </div>

</template>
<script>
import CompOne from './components/CompOne.vue';
import UserInfo from './components/UserInfo.vue';
import Title from "./components/Title.vue";

export default{
    name: 'App',
    components: {
        CompOne,
        UserInfo,
        Title

    }

}


</script>
<style>

</style>