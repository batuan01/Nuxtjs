<template>
  <h1>
    <input type="text" v-model="userId" placeholder="Please enter userId" />
    <button @click="showUser">Go to product</button>
  </h1>
</template>

<script>
export default {
  data() {
    return {
      userId: '1',
    };
  },
  methods: {
    showUser() {
      this.$router.push(`/users/${this.userId}`);
    },
  },
};
</script>

<style></style>
