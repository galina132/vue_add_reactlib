<template>
  <div>
    <griz>
      <griz-col>Column 1</griz-col>
      <griz-col>Column 2</griz-col>
    </griz>
  </div>
</template>

<script>
import { Grid, GridCol } from 'griz'
export default {
  name: 'HelloWorld',
  components: { Grid, GridCol },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
