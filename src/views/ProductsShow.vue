<template>
  <div class="products-show">
    <h1>{{ product.name }}</h1>

  </div>
</template>

<style>
</style>

<script>

  var axios = require('axios');

export default {
  data: function() {
    return {
      products: {}
    };
  },
  created: function() {
    axios
    .get("http://localhost:3000/api/products/" + this.$route.params.id)
    .then(response => {
      this.product = response.data;
    });
  },
  
  methods: {},
  computed: {}
};
</script>