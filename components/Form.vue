<template>
  <div>
      <form action="">
          <h3>{{ formTitle }}</h3>
          <label for="">Password</label>
          <input type="text">
          <label for="">Email</label>
          <input type="text">
          <button> Submit </button>
      </form>
  </div>
</template>

<script>
export default {
    props: ['formTitle']
}
</script>

<style>
    form {
        margin: 0px auto;
        max-width: 60%;
        width: 400px;
        display: grid;
    }
</style>