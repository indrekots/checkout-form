<template>
  <div id="app">
    <nav-header></nav-header>
    <progress-bar></progress-bar>
    <checkout-form></checkout-form>
  </div>
</template>

<script>
import NavHeader from './components/NavHeader';
import ProgressBar from './components/ProgressBar';
import CheckoutForm from './components/CheckoutForm';

export default {
  components: {
    NavHeader,
    ProgressBar,
    CheckoutForm,
  },
};
</script>

<style>
</style>
