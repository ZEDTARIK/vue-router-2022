<template lang="">

<nav class="navbar navbar-expand-lg navbar-dark bg-primary">
  <div class="container-fluid">
    <router-link class="navbar-brand" to="/">VueJS</router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarColor01" aria-controls="navbarColor01" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <div class="collapse navbar-collapse" id="navbarColor01">

      <ul class="navbar-nav me-auto">
        <li class="nav-item">
          <router-link class="nav-link active" to="/">Home
          </router-link >
        </li>
        <li class="nav-item">
       <router-link class="nav-link" to="/about">About  </router-link >
        </li>
      </ul>

    </div>
  </div>
</nav>
</template>
<script>
export default {
    
}
</script>
<style lang="">
    
</style>