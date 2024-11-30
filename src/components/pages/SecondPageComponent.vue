<script>
import '@/assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/FirstPage')
      alert(`Vas a volver a la página anterior. Redireccionando...`)
    },
    goNext(){
      this.$router.push('/ThirdPage')
      alert(`Vas a redireccionarte a la siguiente página mi amor 💙`)
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
          Siempre me acuerdo de los buenos momentos que pasamos juntos en el piso de Oropesa, esa tranquilidad que tenemos tu y yo, esa paz que siempre nos hace falta después de ser persona 'fuertes e independientes' durante mucho tiempo. Esos momentos donde solo nos damos mimitos y lo que no son mimitos 😚.
          <br><br>Estos momentos siempre los agradezco de poderlos tener cada vez que vamos, el poder renova recetitas para poder cocinar más saludable en nuestra futura casa. Ver series o pelis juntitos calentitos cuando vamos en invierno. Me encantada TODO a ver cuando podemos volver a disfrutar de nuestro pisito 💙
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
