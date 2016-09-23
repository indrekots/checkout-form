<template>
  <h3 class="center-align">Your Credit Card Information</h3>
  <div class="row">
    <div class="input-field col s12 m4">
      <input id="cc-number" type="text" placeholder="Credit Card Number" autocomplete="cc-number">
      <label class="active" for="cc-number">Credit Card Number</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="cc-exp-month" type="text" placeholder="MM" autocomplete="cc-exp-month">
      <label class="active" for="cc-exp-month">Expiration Month</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="cc-exp-year" type="text" placeholder="YY" autocomplete="cc-exp-year">
      <label class="active" for="cc-exp-year">Expiration Year</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="cc-csc" type="text" placeholder="Number at the back of your card" autocomplete="cc-csc">
      <label class="active" for="cc-csc">CVV</label>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
    };
  },
};
</script>

<style>
</style>
