<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
 
</template>

<style>
button {
  cursor:pointer;
  background-color:#4681f4;
  color:white;
  border-radius:10px;
  padding:6px;
  font-size:25px;
  font-weight:bold;
  text-align:center;
  width:14%;
  
}

.outline {
 justify-content:center;
 display:flex;
 min-height:400px;
}

.lecard{
 text-align: center;
 border: solid grey 6px;
 max-width:400px;
 border-radius: 20px;
 margin-bottom: 10px;
 font-size:20px;
 background-color:white;
}
img{
  width: 350px;
}

@media screen and (min-width:501px) and (max-width:800px) {

}
@media screen and (max-width:500px) {
  .lecard{
    font-size: 5vw
  }
}
.buttons {
  margin: 16px auto;
  display: flex;
  align-items: center;
  justify-content: space-evenly; 
}
button:hover{
  background-color:red;
}
button:focus{
 background-color:red;
}
</style>
