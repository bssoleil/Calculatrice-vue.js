<template>
  <div class="calculatrice">
    <h1>Calculatrice</h1>
    <div class="display">0</div>
    <div class="btn">C</div>
    <div class="btn">+/-</div>
    <div class="btn">%</div>
    <div class="btn">/</div>
    <div class="btn">7</div>
    <div class="btn">8</div>
    <div class="btn">9</div>
    <div class="btn">*</div>
    <div class="btn">4</div>
    <div class="btn">5</div>
    <div class="btn">6</div>
    <div class="btn">-</div>
    <div class="btn">1</div>
    <div class="btn">2</div>
    <div class="btn">3</div>
    <div class="btn">+</div>
    <div class="btn zero">0</div>
    <div class="btn">.</div>
    <div class="btn">=</div>
  </div>
</template>

<script>
  export default {
    name: "Calculatrice",
    data() {
      return {

      }
    }
  }
</script>

<style scoped lang="scss">
.calculatrice {
display: grid;
grid-template-columns: repeat(4, 1fr);
grid-auto-rows: minmax(50px, auto);
width: 500px;
margin: 0 auto;
}

.display {
  grid-column: 1/5;
background-color: gray;
color: #000;
}

.zero {
  grid-column: 1/3;
}

.btn {
border: 1.5px solid #000;
background-color: lightgray;
}





</style>
