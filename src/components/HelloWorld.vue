<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h2>Profile Links</h2>
    <ul>
      <li>
        <a
          href="https://atcoder.jp/users/jjjjjjjtgpptmjj"
          target="_blank"
        >
          AtCoder
        </a>
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'This website is for introduction of knagakura'
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
