<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>
      Participantes:
    </h2>
    <p>
      <a href="https://github.com/DiegoCAlvaradoC" target="_blank" rel="noopener"
        >Diego Alvarado Callisaya</a
      >.
    </p>
    <br>
    <p>
      <a href="https://github.com/JuancaJcA" target="_blank" rel="noopener"
        >Juan Carlos Avila</a
      >.
    </p>
    </br>
    
    <br>
    <p>
      <a href="https://github.com/AleFlores15" target="_blank" rel="noopener"
        >Alejandro Flores</a
      >.
    </p>
    </br>
    
    <br>
    <p>
      <a href="https://github.com/TheAlanMC" target="_blank" rel="noopener"
        >Chris Alan</a
      >.
    </p>
    </br>
    <h3>Essential Links</h3>
    <ul>
      <li>
        <a href="https://vuejs.org" target="_blank" rel="noopener">Core Docs</a>
      </li>
      <li>
        <a href="https://forum.vuejs.org" target="_blank" rel="noopener"
          >Web</a
        >
      </li>
      <li>
        <a href="https://stackblitz.com/edit/vue-fushzw?file=README.md" target="_blank" rel="noopener"
          >Stackblitz</a
        >
      </li>
      <li>
        <a href="https://twitter.com/vuejs" target="_blank" rel="noopener"
          >Chris</a
        >
      </li>
      <li>
        <a href="https://news.vuejs.org" target="_blank" rel="noopener">News</a>
      </li>
    </ul>
       <h3>Docente: Rolando Marcelo Ticona Barroso</h3> <br>
    <h3>Fecha de Entrega: 06/10/2022 </h3> <br>
    <h3>Semestre 2-2022 </h3> <br>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
