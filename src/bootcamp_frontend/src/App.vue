<template>
  <main>
    <img src="/logo2.svg" alt="DFINITY logo" />
    Hi
    <br/>
    <button @click="upper">upper</button>
      {{ counter }}
  </main>
</template>

<script>
export default {
  data() {
    return {
      counter: 0
    }
  },
  methods: {
    upper() {
      this.counter++
    }
  }
}
</script>
