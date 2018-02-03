<template>
  <div class="left-nav">
    <ul>
        <li>
           <router-link :to="{name:'Pos'}"><i class="icon iconfont icon-home"></i>首页</router-link>
        </li>
        <li>
            <router-link :to="{name:'Shouyin'}"><i class="icon iconfont icon-goumai"></i>收银</router-link>
        </li>
        <li>
            <router-link :to="{name:'Dianpu'}"><i class="icon iconfont icon-dianpu"></i>店铺</router-link>
        </li>
        <li>
           <router-link :to="{name:'Goods'}"><i class="icon iconfont icon-hanbao"></i>商品</router-link>
        </li>
        <li>
           <router-link :to="{name:'Huiyuan'}"><i class="icon iconfont icon-huiyuanqia"></i>会员</router-link>
        </li>
        <li> 
            <router-link :to="{name:'Tongji'}"><i class="icon iconfont icon-tongji4"></i>统计</router-link>
        </li>
        <li>
           <router-link :to="{name:'Shezhi'}"><i class="icon iconfont icon-gongnengjianyi"></i>设置</router-link>
        </li>
    </ul>
  </div>
</template>
<script>
export default {
  
}
</script>
<style>
    *{
         text-decoration: none;
    }
    .left-nav{
        color:#fff;
        font-size:10px;
        height: 100%;
        background-color: #1D8CE0;
        float:left;
        width:5%;
    }
    .iconfont{
        font-size:24px;
    }
    .left-nav ul{
        padding:0px;
        margin:0px;
    }
    .left-nav li{
        list-style:none;
        color:#FFF;
        font-weight: bold;
        text-align: center;
        border-bottom: 1px solid #20a0ff;
        padding: 10px;
    }
     .left-nav li i{
       display: block;
       color:#fff;
       font-weight: normal;
    }
   
</style>


