<template>
  <section class="form">
    <contact-info></contact-info>

    <div class="row">
      <h3>Your Shipping Address</h3>
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

    <h3>Your Credit Card Information</h3>
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

    <h3>Your Billing Address</h3>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="bill-first-name" type="text" placeholder="John" autocomplete="given-name" required>
        <label class="active" for="bill-first-name">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-last-name" type="text" placeholder="Smith" autocomplete="family-name" required>
        <label class="active" for="bill-last-name">Last Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-company" type="text" placeholder="Company Name" autocomplete="organization">
        <label class="active" for="bill-company">Company</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-address" type="text" placeholder="221B Baker Street" autocomplete="street-address">
        <label class="active" for="bill-address">Address</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-city" type="text" placeholder="London" autocomplete="on">
        <label class="active" for="bill-city">City</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-state" type="text" placeholder="State/Province" autocomplete="on">
        <label class="active" for="bill-state">State/Province</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-postal" type="text" placeholder="Postal Code" autocomplete="postal-code">
        <label class="active" for="bill-postal">Postal Code</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="bill-country" type="text" placeholder="Narnia" autocomplete="country">
        <label class="active" for="bill-country">Country</label>
      </div>
    </div>


  </section>
</template>

<script>
import ContactInfo from './ContactInfo';

export default {
  components: {
    ContactInfo,
  },
  data() {
    return {
    };
  },
};
</script>

<style scoped>
</style>
