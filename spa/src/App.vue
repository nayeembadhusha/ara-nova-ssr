<template>
  <div id="app">
  <div id="test_revert">
    <nav class="navbar has-shadow" role="navigation" aria-label="main navigation">
      <div class="container">
        <div class="navbar-menu">
          <router-link class="navbar-item" to="/">Home</router-link>
          <router-link class="navbar-item" to="/about">About</router-link>
        </div>
      </div>
    </nav>
    <br/>
    <router-view></router-view>
  	</div>
  </div>
</template>

<script>

export default {
  name: 'app'
}
</script>
