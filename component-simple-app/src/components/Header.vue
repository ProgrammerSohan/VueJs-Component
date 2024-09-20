<template>
    <div class="myHeader"> 
        <h1>Programmer Sohan</h1>
        <nav>
            <ul>
                <li><a href="">Home</a></li>
                <li><a href="">About</a></li>
                <li><a href="">Skills</a></li>
                <li><a href="">Services</a></li>
                <li><a href="">Contact</a></li>

            </ul>
        </nav>
        
    </div>
</template>
<script>
export default {
    name: "Header",
    
}
</script>
<style scoped>
.myHeader{
    height: 60px;
    display:flex;
    justify-content: center;
    align-items: center;
    color: black;
    background: rgb(234,232, 232);
    padding: 8px;
    font-size: 20px;
    border-bottom: 1px solid grey;

}
.myHeader h1{
   margin-right: auto;
   padding-left: 50px;

}
.myHeader nav ul{
    display: flex;
    margin-right:50px;

}
.myHeader nav ul li{
    list-style: none;
    margin-right:15px;
}
.myHeader nav ul li:hover{
    background:rgb(197, 180, 148);
    
}
.myHeader nav ul li a{
    text-decoration: none;
    cursor: pointer;
    font-size: 25px;
    font-weight: bold;
}
.myHeader nav ul li a:hover{
    color:white;
}
    
</style>