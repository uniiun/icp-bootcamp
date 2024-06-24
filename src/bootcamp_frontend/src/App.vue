<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    <h1 style="text-align: center;">cosik tu jest</h1>
    <br>
    <button @click="zwieksz">+1 byczq</button>
    {{ licznik }}
  </main>
</template>

<script>
  export default{
    data() {
      return{
        licznik: 0
      }
    },
    methods:{
      zwieksz(){
        this.licznik++
      }
    }
  }
</script>