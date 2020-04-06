<template>
  <div>
    <h3>Edit the User</h3>
    <p>Locale: {{ $route.query.local }}</p>
    <p>Analytics: {{ $route.query.q }}</p>
    <!-- <div style="height: 1700px;"></div> -->
    <p id="data">Some data</p>
    <button class="btn btn-danger">Confirm</button>
  </div>
</template>
