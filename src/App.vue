<template>
  <nav id="nav">
    <router-link to="/">Home</router-link> |
    <router-link :to="{ name: 'about' }">About</router-link> | 
    <router-link :to="{ name: 'project'}">Project</router-link>
  </nav>
  <router-view/>
</template>

<style>
@import "/public/style.css";
</style>
