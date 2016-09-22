<template>
  <div id="app">
    <nav-header></nav-header>
    <progress-bar></progress-bar>
    <checkout-form></checkout-form>
    <order-review></order-review>
  </div>
</template>

<script>
import NavHeader from './components/NavHeader';
import ProgressBar from './components/ProgressBar';
import CheckoutForm from './components/CheckoutForm';
import OrderReview from './components/OrderReview';

export default {
  components: {
    NavHeader,
    ProgressBar,
    CheckoutForm,
    OrderReview,
  },
};
</script>

<style>
</style>
