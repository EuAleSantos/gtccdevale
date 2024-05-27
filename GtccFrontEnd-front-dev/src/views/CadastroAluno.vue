<template>
    <body>
        <div class="container">    
            <div class="workspace">
                <div class="head">Cadastro de Alunos
                    <button class="btn-action">></button>
                </div>
            
                <div class="forms">
                    <form class="form-addaluno">
                        <input class="input-addaluno" style="width:  150px;" type="text" placeholder="Nome Completo">
                        <input class="input-addaluno" style="width:  110px;" type="text" placeholder="Matricula">
                        <input class="input-addaluno" style="width:  110px;" type="date" placeholder="Data de Nascimento">
                        <input class="input-addaluno" style="width:  90px;" type="tel" placeholder="Contato">
                        <input class="btn-default btn-search" type="button" value="ADD">
                    </form>
                    <table border="1">
                        <tr class="table-title">
                            <td>Nome</td>
                            <td>Matricula</td>
                            <td>Data de nascimento</td>
                            <td>Contato</td>
                        </tr>
                        <tr>
                            <td>Alessandro santos</td>
                            <td>6922203779</td>
                            <td>15/03/2001</td>
                            <td>279999999</td>
                        </tr>
                    </table>
                </div> 
            </div>
        </div>
    </body>
</template>
  
<script>
    export default{
        name: 'CadastroAluno'
    }
</script>

