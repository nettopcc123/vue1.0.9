<template>
<div id="favorites">
    <h2 class="uitit_a fmt30">我的粉丝</h2>
    <div class="favors">
     暂无粉丝
    </div>
 </div> 
 </template>
<script>
import axios from 'axios'
export default {
  name:'favorites',
  data(){
    return {
      weather:[]
    }
  },
  mounted:function(){
    this.$nextTick(function(){
     
    })
  },
  methods:{
  }
}
</script>
<style lang="scss">
@import "scss/base.scss";
.favors{
    display: block;
    text-align: center;
    font-size: 0.14rem;
    color: #4a4a4a;
    margin-top:0.2rem
}
.uitit_a{
    display: block;
    line-height: 0.36rem!important;
    padding-left:0.15rem;
    font-size: 0.18rem;
    text-align: center;
    background:#f1efef !important;
    border-bottom: 1px solid #fff;
    color:#404040;
    font-weight: normal;
}
.fmt30{
  margin-top:0.4rem;
}
</style>