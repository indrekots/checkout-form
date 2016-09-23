<template>
  <section class="form">
    <h3>Contact Information</h3>
    <div class="row">
      <div class="input-field col s12 m4">
        <input id="first-name" type="text" placeholder="John" autocomplete="given-name" autofocus required>
        <label class="active" for="first-name">First Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="last-name" type="text" placeholder="Smith" autocomplete="family-name" required>
        <label class="active" for="last-name">Last Name</label>
      </div>
      <div class="input-field col s12 m4">
        <input id="email" type="email" placeholder="john@smith.com" autocomplete="email" required>
        <label class="active" for="email">Email Address</label>
      </div>
    </div>

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



        <h3>Your Credit Card Information</h3>
        <div class="cc-warning"><em>Note: don't enter any actual credit card info!</em></div>
        <label>Credit Card Number
          <input type="text">
        </label>
        <label>Credit Card Type
          <select name="cc">
            <option>Visa</option>
            <option>American Express</option>
            <option>Mastercard</option>
            <option>Discover</option>
          </select>
        </label>
        <label>Expiration Date
          <input type="text" placeholder="MM"><input type="text" placeholder="YY">
        </label>
        <label>CVV
          <input type="number">
        </label>

        <h3>Your Billing Address</h3>
        <label>First Name
          <input type="text">
        </label>
        <label>Last Name
          <input type="text">
        </label>
        <label>Company
          <input type="text">
        </label>
        <label>Address Line 1
          <input type="text">
        </label>
        <label>City
          <input type="text">
        </label>
        <label>State/Province
          <input type="text">
        </label>
        <label>Postal Code
          <input type="text">
        </label>
        <label>Country
          <input type="text">
        </label>
      </div>

    </div>
  </section>
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
