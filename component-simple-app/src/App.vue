<template>
    <div class="wrapper">
        <Header />
        
        <div class="bottomWrapper">
             <Content />
             <Side />

        </div>
    </div>

</template>
<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import Side from "./components/Side.vue";

export default{
    name: 'App',
       components: {
        Header,
        Content,
        Side

    }

}


</script>
<style>
html,
body{
    margin: 0;
    padding: 0;
    box-sizing: border-box;

}
.wrapper{
  display:flex;
  flex-direction: column;

}
.bottomWrapper{
    display: flex;
}

</style>