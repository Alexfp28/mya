<script lang="ts">
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/first-page')
    },
    goNext(){
      this.$router.push('/third-page')
    }
  },
};



</script>

<template>
  <div class="container pagina-2">
    <h3 class="main-title">Finde en el pisito del amor 🏖️</h3>
    <div class="card">
      <div class="card-section text-section">
        <p class="content">
          Siempre me acuerdo de los buenos momentos que pasamos juntos en el piso de Oropesa con
          esa tranquilidad que tenemos tu y yo. Esa paz que siempre nos hace falta después de ser
          personas 'fuertes e independientes' durante mucho tiempo, que gracias a eso,
          podemos darnos muchos mimitos y lo que no son mimitos... 😚
          <br><br>Estos momentos siempre los agradezco de poderlos tener cada vez que vamos. El poder renovar recetitas para poder cocinar más saludable en nuestra futura casa (Y convertirnos en MasterChefs).
          La verdad que me encanta TODO lo que hacemos alli porque nos hace muy felices.
          <br>A ver cuando podemos volver a disfrutar de nuestro pisito 💙
        </p>
        <p class="content">
          Está chuli la fotito, cuando fue mi cumpleañoss 😊
        </p>
        <div class="buttons">
          <button class="btn" @click="goBack()" >Volver Atrás... 🚹</button>
          <button class="btn" @click="goNext()">Siguiente... 🌊</button>
        </div>
      </div>
      <div class="card-section image-section">
        <img src="/src/images/foto_oropesa.jpg" alt="Oropesa" style="width: 500px; height: 500px;" />
      </div>
    </div>
  </div>
</template>


<style>

</style>
