<script lang="ts">
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/second-page')
    },
    goNext(){
      this.$router.push('/last-page')
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
          ¿Te acuerdas cuando fuimos a Benidorm la primera vez?
          Nos gustó tanto que repetimos de nuevo pero en verano JAJAJAJAJAJAJ. (Que pienso que nos enamoró aún más ese hotel)
          La verdad que esas escapaditas que hacemos nos han dado años de vida y a la vez nos los han quitado con la barbaridad de alcohol
          que hemos estado bebiendo, pero el todo incluido había que amortiguarlo JAJAJAJAJAJ.
          <br><br>Me acuerdo cuando estábamos tumbaditos en la camita abrazaditoss (en esa cama tan grande).
          <br>No nos podemos olvidar de que también nos fuimos a Terra Mitíca subiendo en la misma atracción no sé cuantas veces solo para salir bien en la foto 🤣
          <br><br>Disfrutando del veranito juntos 💙
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
        <img src="/src/images/foto_benidorm.jpg" alt="Benidorm" style="width: 500px; height: 500px;" />
      </div>
    </div>
  </div>
</template>


<style>

</style>
