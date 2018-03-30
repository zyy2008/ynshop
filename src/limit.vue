<template>
<el-container>
  <el-header height>
      <Limithd> </Limithd>
  </el-header>
	<el-main style="background-color:#f5f5f5">
   <Limitmenu> </Limitmenu>
   <Limitlist> </Limitlist>
  </el-main>
  <el-footer height>
    <Footert></Footert>
    <Footerb></Footerb>
  </el-footer>
</el-container>
</template>

<script>
import Limithd from './components/limithd'
import Limitmenu from './components/limitmenu'
import Limitlist from './components/limitlist'
import Ideal from './components/ideal'
import Footert from './components/footert'
import Footerb from './components/footerb'
export default {
  components: {
    Limithd,
    Limitmenu,
    Limitlist,
    Footert,
    Footerb,
  }
};
</script>