<template>
<el-container>
  <el-header height="600px">
      <Header> </Header>
  </el-header>
	<el-main >
    <!-- 限时抢购 -->
     <Snaplist></Snaplist>
    <!-- 首页商品列表 -->
    <Typelist></Typelist>
    <!-- 理想家 -->
    <Ideal></Ideal>
    <!-- 企业采购 -->
    <Purchase></Purchase>
  </el-main>
  <el-footer height>
    <Footert></Footert>
    <Footerb></Footerb>
  </el-footer>
  <Fixed></Fixed>
</el-container>
</template>

<script>
import Header from './components/header'
import Snaplist from './components/snaplist'
import Typelist from './components/typelist'
import Ideal from './components/ideal'
import Purchase from './components/purchase'
import Footert from './components/footert'
import Footerb from './components/footerb'
import Fixed from './components/fixed'
export default {
  components: {
    Header,
    Snaplist,
    Typelist,
    Ideal,
    Purchase,
    Footert,
    Footerb,
    Fixed
  }
};
</script>