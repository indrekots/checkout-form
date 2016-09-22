<template>
  <section class="form">
    <h3>Contact Information</h3>
    <label for="first-name">First Name
      <input id="first-name" type="text" placeholder="John" autocomplete="given-name" autofocus required="">
    </label>
    <label for="last-name">Last Name
      <input id="last-name" type="text" placeholder="Smith" autocomplete="family-name" required>
    </label>
    <label for="email">Email Address
      <input id="email" type="email" placeholder="john@smith.com" autocomplete="email" required>
    </label>

    <h3>Your Shipping Address</h3>
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
    <label>Address Line 2
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
    <label>Address Line 2
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
