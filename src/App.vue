<template>
  <div id="app">
    <nav>
      <ul>
        <li><router-link to="/">Home</router-link></li>
        <li><router-link to="/marketplace">Marketplace</router-link></li>
        <li><router-link to="/create">Create NFT</router-link></li>
        <li><router-link to="/wallet">Wallet</router-link></li>
      </ul>
    </nav>

    <router-view></router-view>
  </div>

  <footer>
  <p>&copy; 2023 Vue NFT Marketplace</p>
</footer>
</template>

<script>
export default {
  name: 'App',
}
</script>

<style>
#app {
  margin: 0 auto;
  max-width: 960px;
}
nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 20px;
}
ul {
  list-style: none;
  display: flex;
}
li {
  margin-right: 20px;
}
a {
  text-decoration: none;
  color: #333;
}
footer {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 50px;
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}

footer p {
  margin: 0;
  font-size: 14px;
}

</style>
