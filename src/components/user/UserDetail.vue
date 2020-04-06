<template>
  <div>
    <h3>Some User Details</h3>
    <p>User loaded has id: {{ id }}</p>
    <hr />
    <router-link :to="link" class="btn btn-primary">Edit User</router-link>
  </div>
</template>

<script>
export default {
  props: ["id"],
  data() {
    return {
      link: {
        name: "userEdit",
        params: { id: this.id },
        query: { local: "en", q: 100 },
        hash: "#data",
      },
    };
  },
};
</script>
