<template>
<div>
  <nav class="navbar navbar-light bg-light">
    <div class="container">
      <nuxt-link class="navbar-brand" :to="{name:'index'}">NIHAO</nuxt-link>
    </div>
    <ul class="navbar-nav mr-auto">
      <li class="nav-item">
        <nuxt-link 
        :to="{name:'posts'}"
        class="nav-link"
        >Posts</nuxt-link>
      </li>
    </ul> 
  </nav>
  <div class="container">
    <nuxt />
  </div>
  </div>
</template>
<style>
.navbar-brand{
  letter-spacing: 2px;
  font-weight: bold;
}

</style>
