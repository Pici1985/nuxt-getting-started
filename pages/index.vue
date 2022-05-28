<template>
  <div>
    <div>
      <Title title="Home"/>
    </div>

    <p>
      {{ $store.state.title }}
    </p>

    <button @click="increment">Increment me! {{ $store.state.counter }}</button>
  </div>
</template>

<script>
export default {
    methods: {
      increment() {
        this.$store.commit('increment')
      }
    }
}
</script>
