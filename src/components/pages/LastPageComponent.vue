<script lang="ts">
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/third-page')
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
          Espero que te haya gustado la experiencia mi amor, la verdad que me ha dado mucha ilusión el poder hacerte esto.
          Ya sabes que voy un poquito falta de tiempo. Pero siempre intento sacarlo para poder ver una sonrisita de esa carita tan bonita que tienes.
          <br><br>De verdad me haces muy feliz Miryam (Bomboncito), sé que no es mucho y es algo diferente a lo que te suelo regalar.
          <br> Eres una pareja que me ha enseñado mucho, no solo a ser mejor persona, sino también a ser mejor un hombre para ti y para la relación.
          <br><br>Sé que cometo fallos, no soy perfecto (todavía 😚).
          <br>Pero si que sé una cosa, que quiero pasar el resto de mi vida contigo.
          Gracias por estos dos añitos y por todos los que nos quedan juntitos mi vida. 💙
        </p>
        <p class="content">
          Nuestra fotito del primer aniversariooo 😊
        </p>
        <div class="buttons">
          <button class="btn" @click="goBack()" >Volver Atrás... 🚹</button>
        </div>
      </div>
      <div class="card-section image-section">
        <img src="/src/images/foto_anyito.jpg" alt="Primer añito" style="width: 500px; height: 500px;" />
      </div>
    </div>
    <h3 class="main-title">💙 YA PUEDES ABRIR TU REGALITOO 💙</h3>
  </div>
</template>


<style>

</style>
