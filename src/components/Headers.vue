<template>
<nav class="navbar navbar-default">
  <div class="container-fluid">
    <div class="navbar-header">
      <a class="navbar-brand" href="#">
         <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#bs-example-navbar-collapse-1">
          <span class="sr-only">Toggle navigation</span>
          <span class="icon-bar"></span>
        </button>
        <logout/>
      </a>
    </div>
  </div>
</nav>
</template>

<script>
import Logout from '@/components/Logout'
export default {
  components: {
    Logout
  }
}
</script>

<style>
.navbar-custom {
    background-color: #ff5500;
}
.log{
  margin: 5px;
}
</style>
