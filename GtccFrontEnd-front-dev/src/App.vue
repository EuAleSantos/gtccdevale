<template>
  <NavBarComponents />
  <router-link to="/">
    Login
  </router-link>
  <router-link to="/dashBoard">
    DashBoard
  </router-link>
  <router-link to="/cadastroTcc">
    CadastroTcc
  </router-link>
  <router-link to="/cadastroAluno">
    CadastroAluno
  </router-link>
  <router-link to="/CadastroBanca">
    CadastroBanca
  </router-link>
  <router-link to="/ConfirmaRelatorio">
    ConfirmaRelatorio
  </router-link>
  <FooterComponents />

  <router-view />
</template>

<script>

  import NavBarComponents from './components/NavBarComponents.vue';
  import FooterComponents from './components/FooterComponents.vue';

  export default {
    name: 'App',
    components: {
      NavBarComponents,
      FooterComponents
    }
  }
</script>

<style>
/* Layout Geral */
body{
    margin: 0;
    padding: 0;
    /* overflow: hidden; */
}


header{
    position: fixed;
}
.head{
    background-color: #09a6a3;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 35px;
    font-size: 30px;
    color: white; 
    font-family: "Poiret One", sans-serif;
    top: 0px;
}

.container{
    width: 100%;
    height: 100vh;
    background: #FCF9D8;
    display: flex;
    align-items: center;
    justify-content: center;
}

.workspace{
    background-color: #ffffff;
    display: grid;
    align-items: top;
    justify-content: center;
    box-shadow: 0 0 1000px 0  #09a6a38e;
    font-family: "Poiret One", sans-serif;
}

.forms{
    font-family: "Poiret One", sans-serif;
    display: flex;
    align-items: top;
    justify-content: center;
    width: 600px;
    margin: 4px;
    margin-top: 25px;
}

.btn-action{
    position: relative;
    background-color: #ffffff;
    border: #09a6a3 solid 1px;
    border-radius: 100px;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 35px;
    height: 35px;
    cursor: pointer;
    font-size: xx-large;
    color: #09a6a3;
    left: 100px;
    top: 18px;
}
.btn-action:hover{
    background-color: #09a6a3;
    color: #ffffff;
}

.btn-default{
    cursor: pointer;
    background-color: #000;
    width: 310px;
    height: 35px;
    padding: 0px;
    padding-right: 10px;
    color: white;
    text-align: right;
    font-size: x-large;
}
.btn-default:hover{
    background-color: #ffffff;
    color: #000;
    border: #0000005e solid 1px;
}

h1{
    font-family: "Poiret One", sans-serif;
    font-size: 70px;
    color: white;
}
    
table,  th, td{
    border: #09a6a3 solid 1px;
    border-collapse: collapse;
    padding: 10px;
    margin-left: 5px;
    margin-right: 5px;
    font-family: "Poiret One", sans-serif;
    text-align: left;
    text-align: center;
    margin-bottom: 5px;
}
.table-title{
    background-color: #09a6a3;
    color: #ffffff;
}


footer{
    position: fixed;
    background-color: rgba(9, 166, 163, 1);
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 35px;
    bottom: 0px;
}

/* Page Login
.container-signin{
    background-image: url(../img/33\ 1.png);
    background-repeat: no-repeat;
    background-size: cover;
    font-family: "Poiret One", sans-serif;
} */

.sec-login {
    background-color: rgba(9, 166, 163, 1);
    width: 300px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 30px;
    margin-right: 500px;
    padding: 30px;
    font-family: "Poiret One", sans-serif;
    text-align: center;
}

input {
    background-color: rgba(237, 235, 201, 1);
    margin-bottom: 30px;
    padding: 5px;
    width: 300px;
    height: 35px;
    border: none;
    font-family: "Poiret One", sans-serif;
    color: #000000;
    font-size: large;
}

/* Page Dashboard */
.search{
    font-family: "Poiret One", sans-serif;
    display: flex;
    align-items: top;
    justify-content: center;
    width: 600px;
    margin: 4px;
    margin-top: 25px;
}

.btn-search{
    width: 77px;
    padding: 5px;
}

/* Page ADD Alunos */

.input-addaluno{
    margin-left: 5px;
    font-size: small;
    height: 25px;
    width: 77px;
    padding: 5px;
}
/* Page ADD Alunos */
.input-cadtcc{
    margin-left: 5px;
    font-size: small;
    height: 25px;
    width: 77px;
    padding: 5px;
}
</style>