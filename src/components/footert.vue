<template>
    <el-container class="el-text-center el-content-center">
    <el-row type="flex" justify="space-around" class="el-footer-t">
        <el-col :span="2">
            <el-card>
                <h3 slot="header">新手指南</h3>
                <div class="el-tabs__header is-left">
                    <div class="el-tabs__item"><a href="http://">注册用户</a></div>
                    <div class="el-tabs__item"><a href="http://">网站订单流程</a></div>
                    <div class="el-tabs__item"><a href="http://">会员特享专享</a></div>
                </div>
            </el-card>
        </el-col>
        <el-col :span="2">
             <el-card class="el-tabs--left">
                <h3 slot="header">如何退款</h3>
                <div class="el-tabs__header is-left">
                    <div class="el-tabs__item"><a href="http://">如何付款/退款</a></div>
                    <div class="el-tabs__item"><a href="http://">常见支付问题</a></div>
                </div>
            </el-card>
        </el-col>
        <el-col :span="3">
            <el-card class="el-tabs--left">
                <h3 slot="header">配送方式</h3>
                <div class="el-tabs__header is-left">
                    <div class="el-tabs__item"><a href="http://">款到快递范围及配送时间</a></div>
                    <div class="el-tabs__item"><a href="http://">货到付款范围及配送时间</a></div>
                    <div class="el-tabs__item"><a href="http://">配送收费标准及验货签收</a></div>
                </div>
            </el-card>
        </el-col>

        <el-col :span="2">
            <el-card class="el-tabs--left">
                <h3 slot="header">售后服务</h3>
                <div class="el-tabs__header is-left">
                    <div class="el-tabs__item"><a href="http://">退换货政策</a></div>
                    <div class="el-tabs__item"><a href="http://">如何办理退换货</a></div>
                    <div class="el-tabs__item"><a href="http://">隐私声明</a></div>
                </div>
            </el-card>
        </el-col>
        <el-col :span="1">
            <div class="el-line"></div>
        </el-col>
         <el-col :span="3">
            <el-card class="el-text-center">
              <img src="../assets/code.jpg" >
              <p>下载云上管家APP有惊喜</p>
            </el-card>
        </el-col>

         <el-col :span="3">
            <el-card>
              <img src="../assets/code.jpg" >
              <p>下载云上管家APP有惊喜</p>
            </el-card>
        </el-col>
    </el-row>
    </el-container>
</template>
<style>
.el-footer-t{
    width: 100%;
    padding-top: 60px;
    padding-bottom: 30px;
}
.el-footer-t a{
    color: #474747;
    text-decoration: none;
    font-size: 12px;
    -webkit-transition: color 0.2s;
    transition: color 0.2s;
}
.el-footer-t a:hover{
    color: #1f9993;
}
.el-footer-t h3{
    font-weight: normal;
    color: #474747;
    font-size: 16px;
    margin-top:0;
     text-align: left;
}
.el-footer-t .el-tabs__header{
 text-align: left;
 
    margin: 0;
}
.el-footer-t .el-card__header{
    padding: 0;
}
.el-footer-t .el-tabs__item{
    padding: 0;
    height: 30px;
    line-height: 30px;
}
.el-footer-t p{
    color: #474747;
    font-size: 13px;
    margin-top: 17px;
}
.el-footer-t .el-col-1{
    width: 1%;
    position: relative;
}
.el-footer-t .el-line{
    width: 1px;
    height: 83px;
    background-color: #474747;
    position: absolute;
    margin: auto;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
}
</style>
