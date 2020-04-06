<template>
  <div>
    <h3>Some User Details</h3>
    <p>User loaded has id: {{ id }}</p>
    <hr />
    <router-link :to="{ name: 'userEdit', params: { id: id } }" class="btn btn-primary">Edit User</router-link>
  </div>
</template>

<script>
export default {
  props: ["id"],
};
</script>
