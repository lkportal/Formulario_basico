<template>
  <div class="main-application-grid">
      <div class="main-item-grid-flex-conatiner">
        <div class="itens-app">
        <h1 id="h1-app">LkPortal</h1>
        <h2 id="h2-auxiliar-circulo"></h2>
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
  
  grid-template-rows: repeat(1,1fr);
  justify-items: center;
  
}
.main-item-grid-flex-conatiner{
 
 display: flex;
 
  margin: 15px;
  flex-wrap: wrap;
  
  
}
.itens-app{
  border: solid 2px #DEEFE7 ;
  background-color: #DEEFE7;
  height: 500px;
  width: 300px;
  border-radius:15px 1px 1px 15px ;
  text-align: center;
  

}
.formulario-app{
  
  height: 500px;
  width: 300px;
  background-color: #32A89C;
  border-radius: 1px 15px 15px 1px;
}
#h1-app{
  margin-top: 25px;;
 
}
#h2-auxiliar-circulo{
  margin-top: 200px;
  position: relative;
  z-index: 1;
  border: double 5px#159A9C;
  height: 150px;
  width: 150px;
  background-color: #002333;
  left: 75px;
  bottom: 100px;
  border-radius: 100px 100px 100px 100px;
  animation: move 3s alternate-reverse infinite;
}
@keyframes move {
    from{border-color: #002333; background-color:#159A9C ;}
    to{border-color:#159A9C ; background-color: #002333 ;}
}

@media only screen and(max-width:650px) {
   .main-application-grid{
     margin-left: 1rem;
   }
  
}



</style>