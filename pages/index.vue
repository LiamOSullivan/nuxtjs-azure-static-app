<template>
  <div>
    <div>
      <div class="logos">
        <img src="Terrain-AI logo dark green.png" alt="Terrain-AI logo" />
      </div>
      <h1 class="title">T-AI Auth Test Server</h1>
      <h2 class="subtitle">Click the links to follow the auth flow</h2>
      <div class="links">
        <div>
          <ul>
            <li>
              <a href="/.auth/login/aad">Login</a>
            </li>
            <li>
              <a href="/.auth/logout">Logout</a>
            </li>
            <li>
              <a href="/restricted">Authorised page</a>
            </li>
            <li>
              <a href="/admin">Admin Page</a>
            </li>
            <li>
              <a href="/project">Project A</a>
            </li>
            <li>
              <a href="/.auth/me">My Details</a>
            </li>
            <!-- <li>
              <NuxtLink to="/spa-fallback">Spa Fallback page</NuxtLink>
            </li> -->
            <!-- <li>
              <NuxtLink to="/404">Custom error page</NuxtLink>
            </li> -->
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.links {
  display: flex;
  flex-direction: column;
  padding-top: 15px;
}
ul {
  list-style: none;
  display: flex;
  flex-direction: row;
  margin-bottom: 40px;
  text-align: center;
  justify-content: center;
}
li {
  padding: 0 20px;
  font-size: 200%;
}
svg {
  padding-right: 20px;
}
img {
  height: 240px;
  margin-bottom: 120px;
}
</style>
