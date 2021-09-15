<template>
  <h1>Job details page</h1>
  <p>Job id is {{ $route.params.id }}</p>
</template>

<script>
export default {
  data() {
    return {
      props: ["id"],
      id: this.$route.params.id,
    };
  },
};
</script>

<style>
</style>