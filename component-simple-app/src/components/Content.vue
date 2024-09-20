<template>
    <div class="contentWrapper">
        <h3>Content</h3>
        <Card />
        <Card />
    </div>
</template>
<script>
import Card from "./Card.vue";
export default {
    name: "Content",
    components:{
        Card,
    }
    
}
</script>
<style scoped>
 .contentWrapper{
    height: calc(100vh - 77px);
    flex: 2;
    display: flex;
    flex-direction: column;
    background: rgb(179, 175, 175);

 }
    
</style>