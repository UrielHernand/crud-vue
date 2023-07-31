<template>
  <div class="port">
      <ul class="logo">
          <li ><img alt="Vue logo" src="../assets/logo.png" class="img"></li>
          <li><h1>UNIVERSIDAD TECNOLÓGICA DE TEHUACÁN</h1></li>
          <li ><img alt="Vue logo" src="http://uttehuacan.edu.mx/web/images/logo_2020p.png" class="img1"></li>
      </ul>

    <div class="datos">
        
        <h1>Desarrollo de software Multiplataforma</h1>
        <h2>Aplicaciones Web Orientada a Servicios</h2>
        <h2>Práctica 05-APP Vue ROUTER</h2>
        <h2>Uriel Hernández Carrera  4 "B"</h2>
        <h1>*</h1>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQUdu-iiaceQ525TrShtUilm428ANBrFmuqUkl-Xub69q1rgY3G2lubQXJ3eoeUBQf0yzc&usqp=CAU" class="img2" alt="">

    </div>

    
      



  </div>
</template>

<script>
export default {
    name:'Portada',
    data(){
        return{
            query:''
        }
    }

}
</script>

<style>
.logo{
    height: 90%;
    justify-content: space-between;
    
    display: flex;
    
    list-style: none;
    margin-left: 10%;
    width: 100%;



}
.img, .img1{
  height: 58%;
}
.port{
    margin-top: 0%;
    height: 100%;
    margin: auto;
}
.img1{
    border-radius: 80px;
    margin-left: 10%;

}
.img2{
    width: 20%;
    margin-left: 40%;
    margin-bottom: 10%;
    border-radius: 69px;
    
}
.datos{
    margin: auto;
    margin-left: 150px;
    

}

</style>