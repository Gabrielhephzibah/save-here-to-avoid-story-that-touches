<template>
   <div id="app">
    <sidebar/>
    <navbar/>
    <invoice/>
    <graph1/>
    <graph2/>
    <div>
      <router-view/>
    </div>
  </div>
</template>
<script>
import sidebar from '@/components/sidebar.vue';
import navbar from '@/components/navbar.vue';
import invoice from '@/components/invoice.vue';
import graph1 from '@/components/graph1.vue';
import graph2 from '@/components/graph2.vue';

export default {
  name: 'App',
  components: {
    sidebar,
    navbar,
    invoice,
    graph1,
    graph2

  }
}
</script>


<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
