<template>
  <div id="app">
    <home></home>
  </div>
</template>

<script>
import Home from './components/Home'
import './../static/home.css'
export default {
  name: 'app',
  components: {
    home: Home,
  }
}
</script>

