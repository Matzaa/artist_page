<template>
  <div>
    <b-nav>
      <b-nav-item>
        <NuxtLink :active="$route.name == 'Home'" to="/Home">Home</NuxtLink>
      </b-nav-item>
      <b-nav-item>
        <NuxtLink :active="$route.name == 'About'" to="/inkandpaint"
          >Ink and Paint</NuxtLink
        >
      </b-nav-item>
    </b-nav>
    <router-view />
  </div>
</template>

<script>
export default {}
</script>

<style></style>
