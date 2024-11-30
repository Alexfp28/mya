<script lang="ts">
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/SecondPage')
      alert(`Vas a volver a la página anterior. Redireccionando...`)
    },
    goNext(){
      this.$router.push('/LastPage')
      alert(`Vas a redireccionarte a la última página mi amor 💙`)
    }
  },
};



</script>

<template>
  <div class="container pagina-3">
    <h3 class="main-title">Viajecitos a Benidorm 🍹️</h3>
    <div class="card">
      <div class="card-section text-section">
        <p class="content">
          ¿Te acuerdas cuando fuimos a Benidorm la primera vez? Nos gustó tanto que repetimos de nuevo pero en verano JAJAJAJAJAJAJ. La verdad que esos viajecitos nos han dado años de vida y nos los han quitado con la barbaridad de alcohol que estabamos bebiendo, pero el todo incluido había que amortiguarlo JAJAJAJAJAJ.
          <br><br>Cuando estabamos tumbaditos en la camita abrazaditoss, también yendo a Terra Mítica inclusive. Disfrutando del veranito juntos 💙
        </p>
        <p class="content">
          La fotito es de la primera vez que fuimoss 😊
        </p>
        <div class="buttons">
          <button class="btn" @click="goBack()" >Volver Atrás... 🚹</button>
          <button class="btn" @click="goNext()">Siguiente... 🌊</button>
        </div>
      </div>
      <div class="card-section image-section">
        <img src="/src/images/foto_benidorm.jpg" alt="Benidorm" style="width: 400px; height: 400px;" />
      </div>
    </div>
  </div>
</template>


<style>

</style>
