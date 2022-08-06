<template>
<!-- the following div contains the two sections  -->
    <div>
        <!-- logo section is for displaying the logo  -->
        <section>Logo</section>
        <!-- the following section contains the options to choose for navigating the website -->
        <section>
            <a href="#Home">Home</a>
            <a href="#About">About</a>
            <a href="#contact">Contact</a>
            <a href="#Location">Location</a>
        </section>
    </div>
</template>

<script>
    export default {
    }
</script>

<style  scoped>
div{
    background-color: antiquewhite;
    display: grid;
    grid-auto-flow: column;
    justify-items:start;
}

section{
    display: grid;
    grid-auto-flow: column;

}
section:nth-of-type(1){
    display: grid;
    justify-self: center;
    padding:30px;
}
section:nth-of-type(2){
    justify-self: end;
}
a{
    text-decoration: none;
    padding: 30px;
}
</style>