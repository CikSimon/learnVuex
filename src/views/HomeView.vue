<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <div class="counter">
      {{ $store.state.counter }}
    </div>
    <div class="buttons">
      <button @click="$store.dispatch('decreaseCounter')">-</button>
      <button @click="$store.dispatch('increaseCounter')">+</button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HomeView'
}
</script>
