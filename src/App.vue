<script setup lang="ts">

</script>

<template>
  <div class="container">
    <nav>
      <ul>
        <li><strong>Kitchen App</strong></li>
      </ul>
      <ul>
        <li><RouterLink to="/">Home</RouterLink></li>
        <li><RouterLink to="/products">Products</RouterLink></li>
        <li><RouterLink to="/categories">Categories</RouterLink></li>
      </ul>
    </nav>
    <RouterView />
  </div>
</template>
