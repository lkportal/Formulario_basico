<template>
    <div class="inputs-formulario">
        <div id="ip1">
            <input type="text" placeholder="Primeiro Nome">
        </div>
         <div id="ip2">
            <input type="text" placeholder="Segundo Nome">
         </div>
         <div id="ip3">
            <input type="text" placeholder="Email">
         </div>
         <div id="ip4">
            <input type="text" placeholder="Confirme o Email">
         </div>
         <div id="ip5">
            <input type="password" placeholder="Digite a Senha">
         </div>
         <div id="ip6">
            <input type="password" placeholder="Confirme a Senha">
         </div>
    </div>
    
</template>

<script>

export default{
    name:'InputText'
}
</script>

<style>

.inputs-formulario{
   position: relative;
   right: 20px;
   height: 25px;
   left:40px;
}
.inputs-formulario input[type=text],input[type=password]{
   background-color: beige;
   height: 40px;
   width: 200px;
   margin:8px;
   border-radius: 5px;
   border: solid 1px gray;
   
}




</style>