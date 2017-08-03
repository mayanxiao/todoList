<style scoped lang="less">
* {
  margin: 0;
  box-sizing: border-box;
}
.post {
  max-width: 960px;
  background-color: pink;
  margin:0px auto; 
  .postbox {
    background-color: grey;
    margin:10px;
    width: 300px;
    height: 200px;
    float: left;
    overflow: hidden;
  }
}

</style>


<template>
  <div class="post">
<<<<<<< HEAD
      <div class="postbox" v-for="p in posts">
        <h1>{{ p.title}}</h1>
        <p>{{p.description}}</p>
      </div>
=======
    <!--   <div class="postbox" v-for="p in posts">
        <h1>{{ p.title}}</h1>
        <p>{{p.description}}</p>
      </div> -->
>>>>>>> HenzoRobin/master
  </div>
</template>


<script>
<<<<<<< HEAD
import $ from 'jquery'
=======
// import $ from 'jquery'
>>>>>>> HenzoRobin/master
export default {
  data:function(){
    return {
      posts:[]
    }
  },
<<<<<<< HEAD
  mounted(){
    $.get('http://awiclass.monoame.com/api/command.php?type=get&name=post').then(function(res){
      this.posts = JSON.parse(res)
      console.log(this.posts) 
    })
  }
=======
  // mounted(){
  //   $.get('http://awiclass.monoame.com/api/command.php?type=get&name=post').then(function(res){
  //     this.posts = JSON.parse(res)
  //     console.log(this.posts) 
  //   })
  // }
>>>>>>> HenzoRobin/master
}

</script>