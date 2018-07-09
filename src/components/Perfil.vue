<template>
    <div>
      <img src="../assets/logo.png" alt="foto usuário" width="100%">
      <p class="text-center">Nome usuário</p>
      <p class="text-center">e-mail usuário</p>
      <p class="text-center">Empresa usuário</p>
      <progress value="70" max="100" ></progress><span>70%Completo</span>
      <hr>
      <ul id="menu-perfil-usuario">
        <li>
          <a class="btn-clear" href="#">Minha Conta Listo</a>
        </li>
        <li>
          <a class="btn-clear" href="#">Domicílio Bancário</a>
        </li>
          <li>
            <a class="btn-clear" href="#">Editar Cadastro</a>
          </li>
          <li>
            <a class="btn-clear" href="#">Alterar Senha</a>
          </li>
          <li>
            <a class="btn-clear" href="#">Editar Foto</a>
          </li>
      </ul>
    </div>
</template>

<script>
    export default {
        name: "Perfil"
    }
</script>

<style scoped>

</style>
