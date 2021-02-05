<template>
  <div id="app">
    <div id="content">
      <div>
        <h1>URLSHOR</h1>
        <p>coming soon</p>
      </div>
    </div>
    
  </div>
</template>

<script>

export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  height: 100vh;
  background-color:papayawhip;
}

#content {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
}

h1 {
  margin: 0;
  animation: spacing 2s infinite alternate;
}

@keyframes spacing {
  0% {
    letter-spacing: 0px;
  }

  100% {
    letter-spacing: 15px;
  }
}
</style>
