<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    siemano kolano bratku, z tej strony antoni co jajami dzwoni pozdrownienia dla rodzinki
    <br>
    {{ licznik }}
    <button @click="podbij">podbij</button>
  </main>
</template>

<script>
export default {
  data() {
    return {
      licznik: 0
    }
  },
  methods: {
    podbij() {
      this.licznik++
    }
  },    
}
</script>