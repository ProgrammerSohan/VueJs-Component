<template>
    <div>

        <UserInfovalidation name="Sohan" surname="Sujan" age="1296" />
    </div>

</template>
<script>
import UserInfovalidation from './components/UserInfovalidation.vue';




export default{
    name: 'App',
    data(){
        return {
            page: "Hello I am Sohan!!",
                      

            
        }
    },
    components: {
        UserInfovalidation

    }

}


</script>
<style>

</style>