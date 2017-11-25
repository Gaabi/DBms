<template>
<div id="user" class="user">
<title>Demand Forecasting</title>
<h1 align=center>Required books in library</h1>
<h2 align=left>Input date</h2>
<p align =left>
</hr>
<label><b>FROM DATE </b>    </label><input type="date" placeholder="mm/dd/yyyy" ></br></br></br>
<label><b>TO DATE    : </b> </label><input type ="date"></br></br></br>
<button class="button" v-on:click="clicked">Submit </button>
</p>
<p> <h3><b >ANALYSIS</b></h3></p>
</hr>

</div>
</template>

<script>
export default {
name :'user',
method :{
    clicked:function(){
        alert ("instead of alert data will be displayed");
    }
}

}
</script>


<style>
.button{
    background-color:#154AA7   ;
    border: none;
    color: white;
    padding: 15px 32px;
    text-align: center;
    text-decoration: none;
    display: inline-block;
    font-size: 16px;
    margin: 4px 2px;
    cursor: pointer;
}
#user{
font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
   color: #2c3e50;

  margin-left:60px;
   background:#33C1FF  ;
  
}
</style>