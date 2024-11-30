<script>
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/ThirdPage')
      alert(`Vas a volver a la página anterior. Redireccionando...`)
    }
  },
};



</script>

<template>
  <div class="container pagina-3">
    <h3 class="main-title">💙 Final de la Experiencia 💙</h3>
    <div class="card">
      <div class="card-section text-section">
        <p class="content">
          Espero que te haya gustado la experiencia, la verdad que me ha dado mucha ilusión el poder hacerte esto. Ya sabes que voy un poquito falta de tiempo. Pero siempre intento sacar tiempo para poder sacarte una sonrisita de esa carita tan bonita que tienes.
          <br><br>De verdad me haces muy feliz Miryam, sé que no es mucho y es algo diferente a lo que te suelo regalar. Pero de verdad gracias por estos dos añitos y por todos los que nos quedan juntitos. 💙
        </p>
        <p class="content">
          Nuestra fotito del primer aniversariooo 😊
        </p>
        <div class="buttons">
          <button class="btn" @click="goBack()" >Volver Atrás... 🚹</button>
        </div>
      </div>
      <div class="card-section image-section">
        <img src="/src/images/foto_anyito.jpg" alt="Primer añito" style="width: 400px; height: 400px;" />
      </div>
    </div>
    <h3 class="main-title">💙 YA PUEDES ABRIR TU REGALITOO 💙</h3>
  </div>
</template>


<style>

</style>
