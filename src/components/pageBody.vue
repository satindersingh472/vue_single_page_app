<template>
  <div>
    <!-- section is inside the div so the template will have only one child -->
    <section>
        <!-- heading with h2 tag -->
      <h2>Web-Development</h2>
      <!-- an img tag  -->
      <img src="../assets/web_development.avif" alt="laptop on a table with coding in the screen">
      <!-- paragraph regarding the above heading -->
      <p>
        Web development is the work involved in developing a website for the
        Internet (World Wide Web) or an intranet (a private network).[1] Web
        development can range from developing a simple single static page of
        plain text to complex web applications, electronic businesses, and
        social network services.
      </p>
      <!-- end of first paragraph -->
        <!-- heading with h2 tag -->
      <h2>Book-Keeping</h2>
      <!-- an img tag of book keeping img -->
      <img src="../assets/bookkeeping.avif" alt="a person writing in a book">
      <p>
        Bookkeeping is the recording of financial transactions, and is part of
        the process of accounting in business and other organizations.[1] It
        involves preparing source documents for all transactions, operations,
        and other events of a business
      </p>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style  scoped>
div{
    display: grid;
    text-align: center;
    background-color:silver;
}
img{
    height: 300px;
    width: 300px;
    object-fit: cover;
}
</style>