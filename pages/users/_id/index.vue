<template>
  <h1>
    {{ $route.params.id }}
  </h1>
</template>

<script>
export default {
  validate({ params }) {
    return /^[0-9]{2,5}$/.test(params.id);
  },
};
</script>

<style></style>
