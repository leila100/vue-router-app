<template>
  <div>
    <h3>Some User Details</h3>
    <p>User loaded has id: {{ id }}</p>
  </div>
</template>

<script>
export default {
  props: ["id"],
};
</script>
