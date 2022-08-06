<template>
<!-- template will contain the html required for the footer which is divided into two sections under the parent div -->
  <div>
    <!-- the following section is about the contact information  -->
    <section>
      <h2>Contact</h2>
      <a href="d@d.com">sam@gmail.com</a>
      <p>call 13213211</p>
      <p><a href="instagram.com">Instagram</a></p>
    </section>
    <!-- the following section is about the services that are offered -->
    <section>
      <h2>Services</h2>
      <p>web-development</p>
      <p>book-keeping</p>
    </section>
  </div>
</template>

<script>
export default {

};
</script>

<style scoped>
div {
  display: grid;
  grid-auto-flow: column;
  place-items: center;
  background-color: gray;
}
</style>