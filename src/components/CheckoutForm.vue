<template>
  <div>
    <form autocomplete="off">
      <label for="Firstname">Firstname:</label>
      <input type="text" name="Firstname" />
      <br />
      <br />
      <label for="Lastname">Lastname:</label>
      <input type="text" name="Lastname" />
      <br />
      <br />
      <label for="Email">Email:</label>
      <input type="email" name="Email" />
      <br />
      <br />
      <label for="Phonenumber">Phone number:</label>
      <input type="text" name="Phonenumber" />
      <br />
      <br />
      <input type="submit" value="Checkout" />
    </form>
  </div>
</template>

<script>
export default {
  name: "CheckoutForm",
};
</script>

<style scoped>
</style>