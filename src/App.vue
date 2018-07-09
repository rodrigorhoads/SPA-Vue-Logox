<template>
  <div id="app" class="container">
    <!--Barra de navegação lateral-->
    <aside id="side-bar" class="coluna-2-media">
      <ul id="menu-sidebar">
        <li>Fazer nova Transação</li>
        <li>Fazer Simulação</li>
        <li>Painel do Cliente</li>
        <li>Meus daddos Cadastrais</li>
        <li>Configurações</li>
      </ul>
    </aside>
    <!--Fim Barra de navegação lateral-->

    <!--Barra de navegação superior -->
    <section class="coluna-10-media">
      <div class="container">
        <nav class="nav-top coluna-12-media">
          <input type="search">
          <ul id="menu-nav-top">
            <li><select name="" id="">
              <option value="">Meu Perfil</option>
              <option value=""></option>
              <option value=""></option>
            </select></li>
            <li>icon user</li>
            <li>icon notification</li>
          </ul>
        </nav>
        <!--Fim Barra de navegação superior -->


        <!--Dados usuário-->
        <section id="perfil" class="coluna-3-media">
          <app-perfil-usuario></app-perfil-usuario>
        </section>
        <!--Fim Dados usuário-->
        <!--Tabs Com Formulários-->
        <section class="coluna-8-media" id="formularios">
          <app-meu-dados-cadastrais></app-meu-dados-cadastrais>
        </section>
      </div>
    </section>
  </div>
</template>

<script>
  import Formularios from './components/Formularios';
  import Perfil from './components/Perfil'

  export default {
    components: {
      'app-perfil-usuario': Perfil,
      'app-meu-dados-cadastrais': Formularios
    },
    data() {
      return {}
    }
  }
</script>

<style lang="scss">

</style>
