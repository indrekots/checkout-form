<template>
  <h3 class="center-align">Your Shipping Address</h3>
  <div class="row">
    <div class="input-field col s12 m4">
      <input id="ship-first-name" type="text" placeholder="John" autocomplete="given-name" required>
      <label class="active" for="ship-first-name">First Name</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-last-name" type="text" placeholder="Smith" autocomplete="family-name" required>
      <label class="active" for="ship-last-name">Last Name</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-company" type="text" placeholder="Company Name" autocomplete="organization">
      <label class="active" for="ship-company">Company</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-address" type="text" placeholder="221B Baker Street" autocomplete="street-address">
      <label class="active" for="ship-address">Address</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-city" type="text" placeholder="London" autocomplete="on">
      <label class="active" for="ship-city">City</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-state" type="text" placeholder="State/Province" autocomplete="on">
      <label class="active" for="ship-state">State/Province</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-postal" type="text" placeholder="Postal Code" autocomplete="postal-code">
      <label class="active" for="ship-postal">Postal Code</label>
    </div>
    <div class="input-field col s12 m4">
      <input id="ship-country" type="text" placeholder="Narnia" autocomplete="country">
      <label class="active" for="ship-country">Country</label>
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

<style scoped>
</style>
