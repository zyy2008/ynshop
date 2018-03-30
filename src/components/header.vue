<template>
  
  <el-container class="el-index-hd">

    <div class="el-container el-header-top">
 <el-row type="flex" justify="space-between">
    <el-col :span="8">
      <div class="el-popper">欢迎来到云上营家电商平台！</div>
    </el-col>
    <el-col :span="8" class="el-text-right">
      <el-breadcrumb separator="|">
        <el-breadcrumb-item><a href="#" target="_blank">商家入驻</a></el-breadcrumb-item>
        <el-breadcrumb-item><a href="#" target="_blank">我的订单</a></el-breadcrumb-item>
        <el-breadcrumb-item><a href="#" target="_blank">账号管理</a></el-breadcrumb-item>
        <el-breadcrumb-item><a href="#" target="_blank">下载APP</a></el-breadcrumb-item>
        <el-breadcrumb-item><a href="#" target="_blank">关于我们</a></el-breadcrumb-item>
      </el-breadcrumb>
    </el-col>
</el-row>
</div>

 <div class="el-container el-header-search">
    <el-row type="flex" justify="space-between">
    <el-col :span="4">
      <img src="../assets/logo.png" >
    </el-col>
    <el-col :span="12" style="line-height:51px">
      <el-input placeholder="请输入内容">
          <el-button slot="append" icon="el-icon-search"></el-button>
      </el-input>
    </el-col>
    <el-col :span="4" class="el-text-right" style="line-height:51px">
      <el-button type="primary" size="medium" round>登录</el-button>
      <el-button size="medium" round>注册</el-button>
    </el-col>
</el-row>
 </div>

 <div class="el-container el-header-menu">
    <el-row type="flex" justify="space-between">
    <el-col :span="16">
      <el-menu   mode="horizontal" >
  <el-menu-item index="1"><a href="#" target="_blank">首页</a></el-menu-item>
  <el-menu-item index="2">
   <a href="#" target="_blank">品牌建材</a>
  </el-menu-item>
  <el-menu-item index="3"><a href="#" target="_blank">品牌家具</a></el-menu-item>
  <el-menu-item index="4"><a href="#" target="_blank">办公用品</a></el-menu-item>
  <el-menu-item index="5"><a href="#" target="_blank">生活超市</a></el-menu-item>
  <el-menu-item index="6"><a href="#" target="_blank">云上营·理想家</a></el-menu-item>
  <el-menu-item index="7"><a href="#" target="_blank" class="el-hot"><img src="../assets/hot.png">企业采购</a></el-menu-item>
</el-menu>
    </el-col>
    <el-col :span="4" class="el-shopcar" >
      <a href="#" target="_blank"><img src="../assets/shopcar.png">购物车</a>
    </el-col>
</el-row>
 </div>

<!-- 轮播图 -->
  <el-carousel trigger="click"  height="580px" :interval="5000">
      <el-carousel-item v-for="item in 4" :key="item">
        <img src="../assets/banner.jpg" class="el-banner-img">
      </el-carousel-item>
    </el-carousel>
    </el-container>
</template>