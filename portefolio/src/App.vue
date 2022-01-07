<template>
  <div id="nav">
    <router-link to="/" class="nav-btn">Home</router-link>
    <router-link to="/about" class="nav-btn">About</router-link>
  </div>
  <router-view/>
  <div id="footer">
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}

#nav {
  padding: 30px;
  display: flex;
  align-content: flex-end;
  flex-direction: row-reverse;
  gap: 40px;

  a {
    font-weight: bold;
    color: #cecece;
    padding: 0;
    text-decoration: none;

    &.router-link-exact-active {
      padding: 0;
    }
  }

  .nav-btn:hover {
    text-decoration: underline;
  }

  .icon {
    width: 30px;
    height: 30px;
  }

}
</style>
