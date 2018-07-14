<template>
  <div>
    <h1>Stock Trader</h1>
    <h3>Buy & Sell Stocks</h3>
    <br>
    <h5><u>How it works?</u></h5>
    <p>Trade or View your Portfolio</p>
    <p>You may save & load your data</p>
    <p>Click on 'End day' to begin a New Day!</p>
    <p>Your Funds: {{ funds }}</p>
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

