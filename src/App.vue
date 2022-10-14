<template>
  <main class="">
    <nav class="  dark:bg-slate-900 pl-2 pr-2 mr-2 ml-2 gap-60 text-green-500">
    <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link>|
    <router-link to= "/services">services</router-link>
  </nav>
  <router-view/>
  </main>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
/*   color: #2c3e50; */
  
}
.custom-shape-divider-top-1665655315 {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    overflow: hidden;
    line-height: 0;
}

.custom-shape-divider-top-1665655315 svg {
    position:flex;
    display: block;
    width: calc(248% + 1.3px);
    height: 246px;
}

.custom-shape-divider-top-1665655315 .shape-fill {
    fill: #F84E00;
}

/** For mobile devices **/
@media (max-width: 767px) {
    .custom-shape-divider-top-1665655315 svg {
        width: calc(197% + 1.3px);
        height: 152px;
    }
}

nav {
  padding: 30px;
  gap:30px;
}

nav a {
  font-weight: bold;
  color: #0de042;
}

nav a.router-link-exact-active {
  color: white;
}
</style>
