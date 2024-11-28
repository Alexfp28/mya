<script>
import '../../assets/page.css'
export default {
  data() {
  },
  methods: {
    goBack() {
      this.$router.push('/')
      alert(`Vas a volver a la página anterior. Redireccionando...`)
    },
    goNext(){
      this.$router.push('/SecondPage')
      alert(`Vas a redireccionarte a la siguiente página mi amor 💙`)
    }
  },
};



</script>

<template>
  <div class="container pagina-1">
    <h3 class="main-title">Escapadita a Valencia 🐬</h3>
    <div class="card">
      <div class="card-section text-section">
        <p class="content">
          Hace 5 meses que fuimos a Valencia a pasar el día en el Oceanogràfic. Fue una experiencia muy bonita para ambos, me lo pasé súper bien. <br>
          Estuvimos charlando, caminando de la mano por los parques, riéndonos, viendo maripositas... 🦋
          <br>Pero para mí lo más importante fue pasar tiempo contigo, verte esa sonrisa que ilumina hasta los confines del universo y poder ver esos ojitos tan bonitos que tienes y que tengo que cuidar. 💙
        </p>
        <p class="content">
          PD: Sales perfecta en la foto 😊
        </p>
        <div class="buttons">
          <button class="btn" @click="goBack()" >Volver Atrás... 🚹</button>
          <button class="btn" @click="goNext()">Siguiente... 🌊</button>
        </div>
      </div>
      <div class="card-section image-section">
        <img src="../../../public/images/QLSG9716.jpg" alt="Valencia" style="width: 450px; height: 400px;" />
      </div>
    </div>
  </div>
</template>


<style>

</style>
