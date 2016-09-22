<template>
  <section class="order-review">
    <h3>Your Order</h3>
    <table class="your-order">
      <tr class="headings">
        <td>Product</td>
        <td>Quantity</td>
        <td>Price</td>
        <td>Total</td>
      </tr>
      <tr>
        <td>Game Console 2015</td>
        <td>1</td>
        <td>$500.00</td>
        <td>$500.00</td>
      </tr>
      <tr>
        <td>Platformer Bros 3D</td>
        <td>1</td>
        <td>$50.00</td>
        <td>$50.00</td>
      </tr>
      <tr class="total">
        <td>Total</td>
        <td>$550.00</td>
      </tr>
    </table>
    <label class="check-correct">Is your order correct?
      <input type="checkbox">
    </label>
    <input id="submit" type="submit">
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
