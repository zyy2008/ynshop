<template>
    <el-container class="el-footer-b">
        <el-card class="el-content-center el-text-center">
            <img slot="header" src="../assets/footer.jpg" >
            <el-breadcrumb separator="|">
                <el-breadcrumb-item ><a href="#">关于我们</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">帮助中心</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">售后服务</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">配送与验收</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">商务合作</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">企业采购</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">开放平台</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">搜索推荐</a></el-breadcrumb-item>
                <el-breadcrumb-item><a href="#">友情链接</a></el-breadcrumb-item>
            </el-breadcrumb>
            <p>云上管家版权所有 ©2016-2018 食品经营许可证：JY13301080169586 </p>
        </el-card>
    </el-container>
</template>
<style>
.el-footer-b{
   background-color: #616161;
   padding-top: 20px;
   padding-bottom: 10px;
   margin: 0 -20px;
}
.el-footer-b a{
    font-size: 12px;
}
.el-footer-b .el-breadcrumb__item .el-breadcrumb__inner a:hover,
.el-footer-b .el-breadcrumb__item:last-child .el-breadcrumb__inner a:hover{
    color: #ffffff;
}
.el-footer-b .el-breadcrumb__separator{
    font-size: 12px;
    color: #ffffff;
}
.el-footer-b p{
    font-size: 12px;
    color: #999999;
    margin-top: 0;
}
</style>