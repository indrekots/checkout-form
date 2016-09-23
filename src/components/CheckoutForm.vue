<template>
  <section class="form">
    <contact-info></contact-info>
    <shipping-addr></shipping-addr>
    <credit-card></credit-card>
    <billing-addr></billing-addr>
  </section>
</template>

<script>
import ContactInfo from './ContactInfo';
import ShippingAddr from './ShippingAddr';
import CreditCard from './CreditCard';
import BillingAddr from './BillingAddr';

export default {
  components: {
    ContactInfo,
    ShippingAddr,
    CreditCard,
    BillingAddr,
  },
  data() {
    return {
    };
  },
};
</script>

<style scoped>
</style>
