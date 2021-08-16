<template>
  <div>
    <div class="flex bg-gray-100 border-b border-gray-300 py-4">
      <div class="container mx-auto flex justify-between">
        <div class="flax">
          <router-link class="mr-4" to="/login" exact>Login</router-link>
          <router-link to="/register">Register</router-link>
          <router-link to="/dashboard">dashboard</router-link>
        </div>
      </div>
    </div>
    <div class="container mx-auto py-2">
      <router-view></router-view>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>