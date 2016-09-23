<template>
  <h3 class="center-align">Enter your contact information</h3>
  <div class="row">
    <div class="input-field col s12 m4 push-m2">
      <input id="first-name" type="text" placeholder="John" autocomplete="given-name" autofocus required>
      <label class="active" for="first-name">First Name</label>
    </div>
    <div class="input-field col s12 m4 push-m2">
      <input id="last-name" type="text" placeholder="Smith" autocomplete="family-name" required>
      <label class="active" for="last-name">Last Name</label>
    </div>
  </div>
  <div class="row">
    <div class="input-field col s12 m8 push-m2">
      <input id="email" type="email" placeholder="john@smith.com" autocomplete="email" required>
      <label class="active" for="email">Email Address</label>
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
