<script>
import '../assets/login.css';
export default {
  data() {
    return {
      username: '',
      password: '',
    };
  },
  methods: {
    login() {
      if (this.username === 'miryamfg03' || this.password === '27/11/2022') {
        alert(`Estás entrando a la experiencia mi amoorr 💙`);
        this.$router.push('/FirstPage');
      } else {
        alert(`Cuidadin cuidadin, hay algo que no has puesto bieen...`)
      }
    },
    forgotPassword() {
      alert('Redirecting to reset password...');
    },
  },
};
</script>

<template>
  <div class="login-container">
    <div class="illustration">
      <div class="circle"></div>
      <div class="person"></div>
      <!--      <div class="leaves"></div>-->
      <img class="zoom" src="../../public/images/token_1.png"/>
    </div>
    <div class="login-form">
      <h2>Bienvenida mi amor!! 💙</h2>
      <p>Entra con la cuenta que te he decido para poder entrar a la experiencia 😊</p>
      <form @submit.prevent="login">
        <div class="form-group">
          <label for="username">Usuario</label>
          <input id="username" v-model="username" type="text" placeholder="Introduce tu usuario mi vida" required />
        </div>
        <div class="form-group">
          <label for="password">Contraseña</label>
          <input id="password" v-model="password" type="password" placeholder="Introduce la contraseña que te he dado :D" required />
        </div>
        <button type="submit" class="btn-login">Inicia Sesión</button>
        <div class="links">
          <a href="#" @click.prevent="forgotPassword">Has olvidado la contraseña?</a>
        </div>
      </form>
    </div>
  </div>
</template>


<style scoped>
</style>
