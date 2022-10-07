<template>
  <div class="main-application-grid">
      <div class="main-item-grid-flex-conatiner">
        <div class="itens-app">
        <h1>LkPortal</h1>
        </div>

        <div class="formulario-app">
        <Infor/>
        </div>

    </div>
  </div>
</template>
<script>
import Infor from './components/forms/Infor'
  export default{
    name:'App',
    components:{
      Infor
    }
  }

</script>
<style>

.main-application-grid{
  margin-top: 200px;
  display:grid;
  border: solid 3px black;
  grid-template-rows: repeat(1,1fr);
  justify-items: center;
  
}
.main-item-grid-flex-conatiner{
 
 display: flex;
  border: solid 2px yellow;
  margin: 15px;
  flex-wrap: wrap;
  
}
.itens-app{
  border: solid 2px #0FC2C0 ;
  background-color: white;
  height: 500px;
  width: 300px;
  text-align: center;

}
.formulario-app{
  
  height: 500px;
  width: 300px;
}

</style>