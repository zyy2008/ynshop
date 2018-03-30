<template>
    <el-container direction="vertical" class="el-fixed">
       <el-tooltip placement="left">
            <div slot="content">
                    <el-card>
                        <img  slot="header" src="../assets/code.jpg">
                        <p>扫码下载<br>云上营家App</p>
                    </el-card>
            </div>
            <el-button><img  src="../assets/fixed_eq.png"></el-button>
           
       </el-tooltip>
      <el-button v-scroll-to="{el:'body',easing: 'ease',duration:3000}" class="el-fixed-up animated"><img  src="../assets/fixed_up.png"></el-button>
      
    </el-container>
</template>
<style>

.el-fixed{
    position: fixed;
    right: 10px;
    bottom:100px;
    z-index: 9999;
}
.el-fixed .el-button{
    border:none;
    width: auto;
    height: auto;
    padding: 0;
}
.el-fixed .el-button:hover,
.el-fixed .el-button:focus{
    background-color: inherit;
}
.el-tooltip__popper.is-dark{
    background-color: #ffffff;
    box-shadow: 0 2px 12px 0 rgba(0,0,0,.1);
}
.el-tooltip__popper .popper__arrow{
    display: none;
}
.el-tooltip__popper p{
    font-size: 14px;
    text-align: center;
    margin-top: 0;
}
.el-fixed-up{
    margin: 0 !important;
    display: none;
    visibility: hidden;
}
.el-fixed-up.el-active{
    display: block;
    visibility:visible;
}
</style>
<script>
export default {
  mounted () {
    // $('.el-main-f a').addClass('active');
    $(window).on('scroll', function(){
      if ($(this).scrollTop() < 200) {
        $('.el-fixed-up').removeClass('fadeInUp').addClass('fadeOutDown');;
      } else {
        $('.el-fixed-up').removeClass('fadeOutDown').addClass('fadeInUp el-active')
      };
      if($('.el-main-l a.active').length==1){
        $('.el-main-tabfixed').addClass('el-active fadeInUp');
      }else{
        $('.el-main-tabfixed').removeClass("el-active fadeInUp");
      };
    })
  }
}
</script>
