<template lang="pug">
  div(class="title")
    body(id="subbody")
      h1 Getting your first Project Yumi 
    Linha
    Description
    Login 
</template>

<script>
import Linha from "../components/Linha.vue";
import Description from "../components/Description.vue";
import Login from "../components/geral/Login.vue";
export default {
  components: {
    Linha,
    Description,
    Login
  }
};
</script>

<style>

.title {
  text-align: center;
  font-weight: 300;
  font-size: 20px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  margin: 50px;
  
}

</style>
