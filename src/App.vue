<template>
  <div>
  <Tabs/>
  <Acc/>
  <Navbar :textColor="'blue'" />
    <Navbar :textColor="'white'" />
  </div>
</template>

<script>

import Tabs from "./components/Tabs.vue"
import Acc from "./components/Acc.vue"
import Navbar from "./components/Navbar.vue"

export default {
  name: 'App',
  components: {
    Tabs,
    Acc,
    
    Navbar
  }
}
</script>

<style>

</style>
