<template>
  <div>
      <h1>trade or view Portfoilio</h1>
      <p>your Funds: {{ funds }}</p>
  </div>
</template>

<script>
export default {
  computed: {
      funds() {
          return this.$store.getters.funds;
      }
  }
}
</script>
