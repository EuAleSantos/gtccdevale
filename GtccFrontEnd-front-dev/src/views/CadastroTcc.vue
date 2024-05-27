<template>
 <body>
    <div class="container">    
  <div class="workspace">
    <div class="head">Cadastro de Alunos
        <button class="btn-action">></button>
    </div>
      <div class="forms">
        <form class="form-cadtcc">
            <div class="input-container-cadastrotcc">
       <input type="number" class="input-preencher1-tcc" placeholder="Número de TCC" />
       <input type="text" class="input-preencher2-tcc" placeholder="Titulo do TCC" />
       <input type="text" class="input-preencher3-tcc" placeholder="Subtitulo do TCC" />
       <textarea class="textarea-tcc" placeholder="Digite um resumo sobre o seu TCC"></textarea> 
      </div>
        </form>
      </div> 
  </div>
</div>

 </body>
</template>

<script>
export default {
 name: "CadastroTcc",
};
</script>'

<style scoped>
.input-preencher1-tcc,
.input-preencher2-tcc,
.input-preencher3-tcc {
 width: 80%; 
 margin: 10px 0; 
}

.textarea-tcc {
 width: 80%; 
 height: 100px; 
 margin: 10px 0; 
 resize: none;
}
</style>
