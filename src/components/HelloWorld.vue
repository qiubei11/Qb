<template>
  <div class="hello">
   <h1>武汉理工大学信息管理与信息系统</h1>
   <h1>{{msg}}</h1>
 </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: '李秋贝信管1601'    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style >

h1 {
  display: flex;
  align-items:center;
  justify-content:center;
  font-size:24px;
  padding:1rem;
  width:28rem; 
}
</style>
