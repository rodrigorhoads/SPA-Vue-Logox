<template>
  <div class="container">
    <!--Tab 1 Formulário Conta Listo-->
    <div id="minha-conta-listo">
      <h2>Minha Conta Listo</h2>
      <div class="coluna-6-media">
        <label for="nome">Nome</label>
        <input type="text" name="nome" id="nome" placeholder="Digite Seu Nome">
      </div>
      <div class="coluna-6-media">
        <label for="nome-fantasia">Nome Fantasia</label>
        <input type="text" name="nome-fantasi" id="nome-fantasia" placeholder="Digite o nome fantasia">
      </div>
      <div>
        <select name="segmento" id="dropdown-segmento">
          <option value="">TI</option>
          <option value="">Sáude</option>
          <option value="">Hotelaria</option>
        </select>
      </div>
      <div>
        <label for="genero">Gênero</label>
        <div id="genero">
          <input type="radio" name="Masculino" id="masculino">Másculino
          <input type="radio" name="Feminino" id="feminino">Feminino
        </div>
      </div>
    </div>
    <!--Fim Tab 1 Formulário Conta Listo-->
    <!--Tab 2 Formulário Dados domicílio bancario-->
    <div id="domicilio-bancário"></div>
    <!--Fim Tab 2 Formulário Dados domicílio bancario-->
    <!--Tab 3 Formulário Editar Cadastro-->
    <div id="editar-cadastro"></div>
    <!--Fim Tab 3 Editar Cadastro-->
    <!--Tab 4 Editar Senha-->
    <div id="-form-senha"></div>
    <!--Fim Tab 4 Editar Senha-->
    <!--Tab 5 Editar Foto-->
    <div id="form-foto"></div>
    <!--Fim Tab 5 Editar Foto-->
  </div>
</template>

<script>
    export default {
        name: "Formularios"
    }
</script>

<style scoped>

</style>
