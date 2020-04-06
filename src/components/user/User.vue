<template>
  <div>
    <h1>The User Page</h1>
    <p>Loaded ID: {{ userId }}</p>
    <button @click="navigateToHome" class="btn btn-primary">Go Home</button>
  </div>
</template>

<script>
export default {
  data() {
    return {
      userId: this.$route.params.id,
    };
  },
  methods: {
    navigateToHome() {
      this.$router.push("/");
    },
  },
};
</script>
