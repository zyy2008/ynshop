<template>
 <el-container class="el-content-center el-limitlist">
  <el-row justify="space-between" type="flex">
    <el-col :span="19">
        <div class="el-list">
            <div class="el-list-hd">
                <h3>限时限量 底价疯抢</h3>
                 <count-down  class="timedown" :current-time="1481450106" :start-time="1481450116" :end-time="1481450126" :tip-text="'距离开始还有'"  :tip-text-end="'距离结束还有'"   :hourTxt="':'" :minutesTxt="':'" :secondsTxt="''"></count-down>
            </div>
            <div class="el-list-bd">
                <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_25.png"></div>
                        <div class="el-goods-text">
                            <h3>日本制造 晶钻玻璃锅4.1L</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>320</b></span> <span class="el-font-e">原价 ¥<em class="line">388</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢18件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>
                 <div class="el-goods el-goods-limit">
                   <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_2.png"></div>
                        <div class="el-goods-text">
                            <h3>网易智造智能插线板</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>79</b></span> <span class="el-font-e">原价 ¥<em class="line">99</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢32件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩63件</span>
                            </div>
                        </div>
                    </div>
                </div>
                 <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_3.png"></div>
                        <div class="el-goods-text">
                            <h3>公牛关错位五孔插座</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>99</b></span> <span class="el-font-e">原价 ¥<em class="line">159</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢18件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_26.png"></div>
                        <div class="el-goods-text">
                            <h3>日本制造 超柔软吸水毛巾</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>32</b></span> <span class="el-font-e">原价 ¥<em class="line">68</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢18件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>

                 <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_8.png"></div>
                        <div class="el-goods-text">
                            <h3>复合材料手枪式气动螺丝批</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>934</b></span> <span class="el-font-e">原价 ¥<em class="line">1699</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢6件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>

                    <div class="el-goods el-goods-limit">
                   <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_27.png"></div>
                        <div class="el-goods-text">
                            <h3>白色恋人实木洗衣柜</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>966</b></span> <span class="el-font-e">原价 ¥<em class="line">1299</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢32件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩63件</span>
                            </div>
                        </div>
                    </div>
                </div>

                 <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_9.png"></div>
                        <div class="el-goods-text">
                            <h3>汇泰龙门把手锁具</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>99</b></span> <span class="el-font-e">原价 ¥<em class="line">159</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢18件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>


                 <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_28.png"></div>
                        <div class="el-goods-text">
                            <h3>齐悦三出水淋浴柱</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>159</b></span> <span class="el-font-e">原价 ¥<em class="line">268</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢18件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div>


                <!-- <div class="el-goods el-goods-limit">
                    <div class="el-goods-info">
                        <div class="el-goods-tag"><span class="el-tag">热卖</span></div> 
                        <div class="el-goods-img"><img src="../assets/goods_28.png"></div>
                        <div class="el-goods-text">
                            <h3>复合材料手枪式气动螺丝批</h3>
                            <div class="el-goods-price"><span class="el-font-b">限时价 ¥<b>235</b></span> <span class="el-font-e">原价 ¥<em class="line">389</em></span></div>
                            <div class="el-goods-price noline">
                                <p>已抢6件</p>
<el-progress :percentage="50" :show-text="false">
              </el-progress>
                            </div>
                            <div class="el-goods-tbtn">
                                <el-button type="primary" size="medium">立即抢购</el-button><span>仅剩109件</span>
                            </div>
                        </div>
                    </div>
                </div> -->
                
            </div>
       </div>
    </el-col>
    <el-col :span="5" class="el-goods-r">
        <div class="font"><img src="../assets/font.jpg"></div>
        <a href="#">
        <div class="el-goods">
            <div class="el-goods-info"><div class="el-goods-tag"><span class="el-tag">热卖</span></div> <div class="el-goods-img"><img src="../assets/goods_30.png"></div> <h3>木书签材料 红木料</h3></div>
            <div class="el-goods-price"><span class="el-font-b"><b>¥320</b></span></div>
        </div>
        </a>
        <a href="#">
        <div class="el-goods">
            <div class="el-goods-info"><div class="el-goods-tag"><span class="el-tag">热卖</span></div> <div class="el-goods-img"><img src="../assets/goods_14.png"></div> <h3>艾米 真皮沙发</h3></div>
            <div class="el-goods-price"><span class="el-font-b"><b>¥1396</b></span></div>
        </div>
        </a>
         <a href="#">
        <div class="el-goods">
            <div class="el-goods-info"><div class="el-goods-tag"><span class="el-tag">热卖</span></div> <div class="el-goods-img"><img src="../assets/goods_31.png"></div> <h3>得力电子面单打印机</h3></div>
            <div class="el-goods-price"><span class="el-font-b"><b>¥680.00</b></span></div>
        </div>
        </a>
    </el-col>
  </el-row>

   </el-container>
</template>
<script>
import CountDown from "vue2-countdown";

export default {
  components: {
    CountDown
  }
};
</script>
