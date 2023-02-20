<template>
  <div>
    <div>
      <!-- <div class="logos">
        <img src="Terrain-AI logo dark green.png" alt="Terrain-AI logo" />
      </div> -->
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
              <a href="/public">Public</a>
            </li>
            <li>
              <a href="/authenticated">Authenticated</a>
            </li>
            <li>
              <!-- accessible to AAD users with administrator role??? -->
              <a href="/admin">Admin</a>
            </li>
            <li>
              <a href="/projects">Projects</a>
            </li>
            <li>
              <a href="/unauthorised">Unauthorised</a>
            </li>
            <li>
              <a href="/unauthorised-error">Unauthorised Error</a>
            </li>
            <li>
              <a href="/.auth/me">Me</a>
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

<script lang="ts">
export default {
  components: {},
  data: () => {
    const data = {};
    return data;
  },
  computed: {},
  methods: {},
  created() {},
  mounted() {},
};
</script>

<style scoped>
.links {
  display: flex;
  flex-direction: row;
  padding-top: 15px;
}
ul {
  list-style: none;
  display: flex;
  flex-direction: row;
  margin-bottom: 72px;
  text-align: center;
  justify-content: center;
  flex-flow: row wrap;
  gap: 32px;
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
