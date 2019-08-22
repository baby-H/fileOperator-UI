<template>

  <div id="app-3">
    <h1>{{ msg }}</h1>
<!--    <p v-if="seen">现在你看到我了</p>-->
  </div>

</template>



<script>


  export default {
    name: 'app-3',
    data() {
      return {
        seen: true,
        msg: "我的第一个"
      }
    }
  }



</script>

