<template>
  <div id="app">
    <nav>
      <span>Vue router links: </span>
      <router-link to="/" exact>Home</router-link>
      <router-link to="/vuelogin">vuelogin</router-link>
      <router-link to="/vueauth">vueauth</router-link>
      <router-link to="/vueprofile">protectedlink</router-link>
      <router-link to="/isLoggedIn">isLoggedIn</router-link>
      <router-link to="/getUser">getUser</router-link>
      <router-link to='/login'>explogin</router-link>
      <router-link to="/about">About</router-link>
      <router-link to="/contacts">Contacts</router-link>
      <router-link to="/!@#$%">404 page</router-link>
    </nav>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'app'
}
</script>
