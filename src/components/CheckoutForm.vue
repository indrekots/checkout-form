<template>
  <section class="form">
    <contact-info></contact-info>
    <shipping-addr></shipping-addr>
    <credit-card></credit-card>



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
import ShippingAddr from './ShippingAddr';
import CreditCard from './CreditCard';

export default {
  components: {
    ContactInfo,
    ShippingAddr,
    CreditCard,
  },
  data() {
    return {
    };
  },
};
</script>

<style scoped>
</style>
