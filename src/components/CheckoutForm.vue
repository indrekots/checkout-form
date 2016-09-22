<template>
  <section class="form">
    <h3>Your Name and Demographic Information</h3>
    <label>First Name
      <input type="text">
    </label>
    <label>Middle Initial
      <input type="text">
    </label>
    <label>Last Name
      <input type="text">
    </label>
    <label>Age
      <select name="age">
        <option>&lt;18</option>
        <option>18-25</option>
        <option>26-35</option>
        <option>36-50</option>
        <option>&gt;50</option>
      </select>
    </label>
    <label>Gender
      <select name="gender">
        <option>Male</option>
        <option>Female</option>
      </select>
    </label>
    <label>Email Address
      <input type="text">
    </label>
    <label>Confirm Email Address
      <input type="text">
    </label>
    <label>Put me on the mailing list?
      <input class="inline" type="checkbox">
    </label>

    <h3>Your Shipping Address</h3>
    <label>First Name
      <input type="text">
    </label>
    <label>Middle Initial
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
    <label>Middle Initial
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
