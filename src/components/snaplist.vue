<template>

<el-container class="el-main-tab  el-text-center" id="el-modle-1">
 


<div class="el-content-center">

  <el-card>
        <div slot="header" class="el-text-center">
      
   <h1>限时抢购</h1>
           
            <el-button class="el-btn-obj" icon="el-icon-refresh">换一批</el-button>
        </div>
        <el-row type="flex" justify="space-around">
        <el-col :span="5">
        <el-card class="el-goods el-text-center">
         
            <div class="el-goods-info">
                <div class="el-goods-tag">
                <el-tag>授权</el-tag>
                </div>
                <div class="el-goods-img">
                  <img src="../assets/goods_1.png">
                </div>
              <h2>楼顶屋顶堵漏王防水涂料</h2>
               </div>
              <div class="el-goods-price">
                  <span class="el-font-b">限时价 ¥<b>170</b></span>
                  <span class="el-font-e">原价 ¥<em class="line">388</em></span>
              </div>
              <div class="el-goods-price noline">
<el-progress :percentage="50" :show-text="false">
              </el-progress>
              <div class="el-font-e">剩余<em> 353</em>件</div>
              </div>
              <el-button type="primary" size="medium" round>立即抢购</el-button>
        </el-card>
  </el-col>
  <el-col :span="5">
      <el-card class="el-goods el-text-center">
         
            <div class="el-goods-info">
                <div class="el-goods-tag">
                <el-tag>授权</el-tag>
                </div>
                <div class="el-goods-img">
                  <img src="../assets/goods_2.png">
                </div>
              <h2>网易智造智能插线板</h2>
               </div>
              <div class="el-goods-price">
                  <span class="el-font-b">限时价 ¥<b>79</b></span>
                  <span class="el-font-e">原价 ¥<em class="line">99</em></span>
              </div>
              <div class="el-goods-price noline">
<el-progress :percentage="50" :show-text="false">
              </el-progress>
              <div class="el-font-e">剩余<em> 353</em>件</div>
              </div>
              <el-button type="primary" size="medium" round>立即抢购</el-button>
        </el-card>
  </el-col>
  <el-col :span="5">
        <el-card class="el-goods el-text-center">
         
            <div class="el-goods-info">
                <div class="el-goods-tag">
                <el-tag>授权</el-tag>
                </div>
                <div class="el-goods-img">
                  <img src="../assets/goods_3.png">
                </div>
              <h2>公牛关错位五孔插座</h2>
               </div>
              <div class="el-goods-price">
                  <span class="el-font-b">限时价 ¥<b>99</b></span>
                  <span class="el-font-e">原价 ¥<em class="line">200</em></span>
              </div>
              <div class="el-goods-price noline">
<el-progress :percentage="50" :show-text="false">
              </el-progress>
              <div class="el-font-e">剩余<em> 353</em>件</div>
              </div>
              <el-button type="primary" size="medium" round>立即抢购</el-button>
        </el-card>
  </el-col>
  <el-col :span="5">
       <el-card class="el-goods el-text-center">
         
            <div class="el-goods-info">
                <div class="el-goods-tag">
                <el-tag>授权</el-tag>
                </div>
                <div class="el-goods-img">
                  <img src="../assets/goods_4.png">
                </div>
              <h2>威克士充电电锤</h2>
               </div>
              <div class="el-goods-price">
                  <span class="el-font-b">限时价 ¥<b>320</b></span>
                  <span class="el-font-e">原价 ¥<em class="line">388</em></span>
              </div>
              <div class="el-goods-price noline">
<el-progress :percentage="50" :show-text="false">
              </el-progress>
              <div class="el-font-e">剩余<em> 353</em>件</div>
              </div>
              <el-button type="primary" size="medium" round>立即抢购</el-button>
        </el-card>
  </el-col>
</el-row>
        <div class="el-card__footer">
            <el-button  round>查看更多 ></el-button>
        </div>
        </el-card>
        </div>
</el-container>
</template>