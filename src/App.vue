<template>
  <div id="app">
    <CheckoutForm />
  </div>
</template>

<script>
import CheckoutForm from "./components/CheckoutForm";

export default {
  name: "App",
  components: {
    CheckoutForm,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
