<template>

      <navbar placement="top">

        <router-link to="/" slot="brand" class="navbar-brand">
          <img src="dist/imgs/Bootue-hr.png" height="25"/>
        </router-link>


        <li>
          <router-link to="/started">
           Get Started
          </router-link>
        </li>

        <li>
          <router-link to="/components">
           Components
          </router-link>
        </li>

        <li>
          <router-link to="/css">
           CSS
          </router-link>
        </li>

        <li>
          <router-link to="/structured">
           Structured
          </router-link>
        </li>

        <li>
          <router-link to="/extend">
            Customize and extend
          </router-link>
        </li>

        <li class="hidden-xs">
          <a href="https://github.com/maestro-server/bootue" target="_blank">
            <svg height="16px" fill="#777" class="octicon octicon-mark-github" viewBox="0 0 16 16" version="1.1"
                 aria-hidden="true">
              <path
                d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0 0 16 8c0-4.42-3.58-8-8-8z"></path>
            </svg>
          </a>
        </li>
      </navbar>

</template>

<style>
.navbar {
  margin-bottom: 0;
}

</style>


<script>
export default {
  data () {
    return {
      placement: 'top',
      type: 'default'
    }
  }
}
</script>
