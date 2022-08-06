<template>
  <div>
    <page-header></page-header>
    <page-body></page-body>
    <page-footer></page-footer>
  </div>
</template>

<script>
import PageHeader from "@/components/pageHeader.vue";
import PageFooter from "@/components/pageFooter.vue";
import PageBody from "@/components/pageBody.vue";

export default {
  components: {
    PageHeader,
    PageFooter,
    PageBody,
  },
};
</script>

<style scoped>
</style>
