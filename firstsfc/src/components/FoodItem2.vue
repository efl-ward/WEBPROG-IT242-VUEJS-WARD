<template>
  <div class= 'Saging'>
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Saging',
      message: 'I like Saging'
    }
  }
};
</script>

<style>
 #app > Saging {
    border: dashed black 3px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: yellow;
  }</style>
