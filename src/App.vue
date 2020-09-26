<template>
  <div class="is-black">
    
    <div class="columns layout">
      <div class="column is-one-fifth has-background-dark ">
        <SideNavbar />
      </div>
      <div class="column has-background-grey-dark">

      </div>
    </div>
    
    <div class="block has-background-primary player">
      <h1> Hello </h1>
    </div>

  </div>
</template>

<script>

import SideNavbar from './components/SideNavbar';

export default {
  name: 'App',
  components: {
    SideNavbar
  }
}
</script>

<style scoped>
  .layout {
    height: 88vh;
  }

  
</style>
  

