<template>
  <div id="app">
    <main>
      <div class="searchbox">
        <input type="text" class="search-bar" placeholder="Search..." />
      </div>
    </main>
  </div>
</template>

<script>


export default {
  name: 'App',
  data () {
    return {
      api_key: '95fbe7def10118cb39bbb1dd372b35f9'
    }
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
  box-sizing: 0;
}
body {
  font-family: 'montserrat',sans-serif;
}

#app{
  background-image: url('./assets/cold-bg.jpg');
}
</style>
