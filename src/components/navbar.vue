<template >
<nav class="navbar navbar-expand-lg bg-dark">
  <div class="container-fluid">
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ">
        <li class="nav-item">
          <router-link class="router" to="/">Home</router-link>
        </li>
        <li class="nav-item ">
          <router-link class="router" to="/about">About</router-link>
        </li>
        <li class="nav-item">
          <router-link class="router" to="/product">Product</router-link>
        </li>
        <li class="nav-item">
            <router-link class="router" to="/contact">Contact</router-link>
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
<style>
.navbar-nav{
    margin: 40%;
}
.router{
    color: aliceblue;
    text-decoration: none;
}

.nav-item :hover{
    color: black;
    transition: 0.4s;
    
}
.navbar{
    height: 10vh;
}

.nav-item{
    
    padding-left: 15%;
}


</style>