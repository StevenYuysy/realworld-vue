<template>
  <nav class="navbar navbar-light">
    <div class="container">
      <a class="navbar-brand" href="index.html">conduit</a>
      <ul class="nav navbar-nav pull-xs-right">
        <li class="nav-item">
          <a class="nav-link" href="">
            <i class="ion-compose"></i>&nbsp;New Post
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">Sign up</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="">Settings</a>
        </li>
        <!-- Add "active" class when you're on that page" -->
        <li class="nav-item active">
          <a class="nav-link" href="">Home</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'RealWorldHeader',
};
</script>

<style scoped>
</style>
