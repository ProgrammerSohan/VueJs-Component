<template>
    <div class="card" :style="{ height: height ? height : ''}">
        <h4>Sohan Sujan</h4>
        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Quas, possimus! Similique esse quaerat delectus natus quis ex quos dolores inventore corporis, obcaecati commodi repellat doloremque, enim error dolorem est placeat.
        </p>
        <p>{{content}}</p>
        
    </div>
</template>
<script>
export default {
    name: "Card",
    props: ["height", "content"],
    
};
</script>
<style scoped>

 .card {
    box-shadow: 0 4px 8px 0 rgba(173, 216, 138, 0.2);
    width: 100%;
    border-radius: 10px;
    background: #fff;
    margin-bottom: 10px;

 }
 .card:hover{
    box-shadow: 0 8px 16px 0 rgba(190, 240, 100, 0.2);

 }
    
</style>