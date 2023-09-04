<template>
  <div>
    <Home/>
    <Buy/>
    <Sale/>
    <Search/>
  </div>
    
</template>

<script>
  import Home from './components/Home.vue'
  import Buy from './components/Buy.vue'
  import Sale from './components/Sale.vue'
  import Search from './components/Search.vue'


  export default{
      name: 'App',
      components: {
        Home,
        Buy,
        Sale,
        Search
      }
  }

</script>