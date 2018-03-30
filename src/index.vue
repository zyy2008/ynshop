
<template>
<div class="page-link">
        <router-link to='/home' class="page-a">首页 </router-link>
        <router-link to='/limit' class="page-a">限时抢购</router-link>
        <router-view></router-view>
</div>
</template>
<style>
.page-link .page-a{
    padding-top:10px;
    font-size: 18px;
}
.page-link .page-a:focus{
    color:red;
}
</style>
