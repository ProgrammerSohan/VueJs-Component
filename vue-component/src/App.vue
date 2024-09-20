<template>
    <div>
        <!--  <UserInfovalidation name="Sohan" surname="Sujan" age="1296" /> -->
          <UserInfovalidation :name="user.name" :surname="user.surname" :age="user.age" />
       
    </div>

</template>
<script>
import UserInfovalidation from './components/UserInfovalidation.vue';




export default{
    name: 'App',
    data(){
        return {
           // page: "Hello I am Sohan!!",
             
           user:{
                // name: "Bishop",
                name: 56,
                surname: "John",
                age: 55,

           }
          

            
        };
    },
    components: {
        UserInfovalidation

    }

}


</script>
<style>

</style>