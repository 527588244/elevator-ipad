<template>
    <div class="web">
        <!-- 页面头部 -->
        <div class="web-header">
            <div class="web-header-box">
                <div class="web-header-box1"></div>
                <div class="web-header-box2"></div>
            </div>
            <div class="web-header-awa"></div>
        </div>
        <!-- 页面主体 -->
        <div class="web-center">
            <!-- 左侧边导航栏 -->
            <div class="web-left">
                <div class="navigation" @click="gotPassenger">
                    <span class="text6">• 乘客电梯</span><br />
                    <span class="text7">passenger elevator</span>
                </div>
                <div class="navigation" @click="gotoVilla">
                    <span class="text6">• 别墅电梯</span><br />
                    <span class="text7">Villa elevator</span>
                </div>
            </div>
            <div class="web-text">
                <!-- 中心标题 -->
                <div class="center-title">
                    <span style="text-align: center">PRODUCT</span>
                    <span
                        >[&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;佳登曼电梯&nbsp;|&nbsp;产品中心
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;]</span
                    >
                </div>
                <!-- 乘客电梯 -->
                <div class="web-passenger">
                    <div class="web-passenger-image"></div>
                    <div class="web-passenger-text">
                        <div class="web-passenger-text1">
                            <span class="chinese">别墅电梯</span
                            >&nbsp;&nbsp;&nbsp;
                            <span class="english"> Villa elevator</span>
                            <hr
                                style="
                                    border: 0.4vw solid rgba(0, 43, 125, 0.85);
                                "
                            />
                            <span class="text3"
                                >主要用于提升生活便捷性、增强家居安
                                全性、提高生活质量以及美化家居环境
                            </span>
                        </div>
                    </div>
                </div>
                <!-- 乘客电梯产品 -->
                <div style="display: flex; flex-direction: column; gap: 5.3vw">
                    <div class="web-passenger-product">
                        <div class="web-passenger-product-box">
                            <div class="web-passenger-product-box-img"></div>
                            <div class="web-passenger-product-box-text">
                                <span>GDMK-01|浅云</span><br />
                                <span
                                    >吊 顶:镜面一体式轿
                                    壁:镜面蚀刻/发纹不锈钢</span
                                ><br />
                                <span>地 板:大理石</span>
                                <div
                                    class="web-passenger-product-box-text-bottom"
                                >
                                    <!-- <button
                                  style="
                                      width: 18.2667vw;
                                      height: 5.3333vw;
                                      border-radius: 6.6667vw;

                                      background: rgb(170, 215, 239);
                                  "
                              >
                                  720度展示
                              </button> -->
                                    <a
                                        href="http://my.3vfang.com/p/share/content.php?m=a3I4MDM5LWl0ZW09NTE2OTQ="
                                        class="button-link"
                                        >720度展示</a
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="web-passenger-product">
                        <div class="web-passenger-product-box">
                            <div class="web-passenger-product-box-img"></div>
                            <div class="web-passenger-product-box-text">
                                <span class="text4">GDMK-01|浅云</span><br />
                                <span class="text5"
                                    >吊 顶:镜面一体式轿
                                    壁:镜面蚀刻/发纹不锈钢</span
                                ><br />
                                <span class="text5">地 板:大理石</span>
                                <div
                                    class="web-passenger-product-box-text-bottom"
                                >
                                    <!-- <button
                                  style="
                                      width: 18.2667vw;
                                      height: 5.3333vw;
                                      border-radius: 6.6667vw;

                                      background: rgb(170, 215, 239);
                                  "
                              >
                                  720度展示
                              </button> -->
                                    <a
                                        href="http://my.3vfang.com/p/share/content.php?m=a3I4MDM5LWl0ZW09NTE2OTQ="
                                        class="button-link"
                                        >720度展示</a
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                    <div class="web-passenger-product">
                        <div class="web-passenger-product-box">
                            <div class="web-passenger-product-box-img">
                                <img src="@/assets" alt="浅云" />
                            </div>
                            <div class="web-passenger-product-box-text">
                                <span>GDMK-01|浅云</span><br />
                                <span
                                    >吊 顶:镜面一体式轿
                                    壁:镜面蚀刻/发纹不锈钢</span
                                ><br />
                                <span>地 板:大理石</span>
                                <div
                                    class="web-passenger-product-box-text-bottom"
                                >
                                    <!-- <button
                                  style="
                                      width: 18.2667vw;
                                      height: 5.3333vw;
                                      border-radius: 6.6667vw;

                                      background: rgb(170, 215, 239);
                                  "
                              >
                                  720度展示
                              </button> -->
                                    <a
                                        href="http://my.3vfang.com/p/share/content.php?m=a3I4MDM5LWl0ZW09NTE2OTQ="
                                        class="button-link"
                                        >720度展示</a
                                    >
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {};
    },
    methods: {
        gotoVilla() {
            this.$router.push("/product/Villa");
        },
        gotPassenger() {
            this.$router.push("/");
        },
    },
};
</script>

<style scoped>
.web {
    width: 100%;
    height: 100%;
    box-sizing: border-box;
}
.web .web-header {
    height: 9.33vh;
    background-color: pink;
    position: relative;
    width: 100vw;
    min-width: 750px;
}
.web .web-header .web-header-box {
    width: 80px;
    height: 40px;
    background: whitesmoke;
    display: flex;
    flex-direction: row;
}
.web .web-header .web-header-awa {
    /* 小马 */
    width: 156px;
    height: 64px;
    top: 0;
    right: 0;
    position: absolute;
    background-image: url(@/assets/images/logo.png);
    background-size: cover;
    background-repeat: no-repeat;
}

.web .web-header .web-header-box .web-header-box1 {
    /* 椭圆 1 */
    width: 4.7vw;
    height: 40px;
    left: 13px;
    right: 31.7104px;
    top: 17px;
    bottom: -17px;
    background: rgb(117, 171, 227);
    border-radius: 50%; /* 设置圆形 */
    text-align: center;
    background-image: url(@/assets/images/right.png);
    background-size: cover;
    background-repeat: no-repeat;
}
.web .web-header .web-header-box .web-header-box2 {
    /* 椭圆 2 */
    margin-left: 5px;
    width: 35.2896px;
    height: 40px;
    left: 13px;
    right: 31.7104px;
    top: 17px;
    bottom: -17px;
    box-shadow: 0px 4px 4px 0px rgba(0, 0, 0, 0.18);
    background: rgb(255, 255, 255);
    border-radius: 50%; /* 设置圆形 */
    text-align: center;
    background-image: url(@/assets/images/left.png);
    background-size: cover;
    background-repeat: no-repeat;
}

.web .web-text {
    width: 59.6vw;
    height: auto;
    margin-left: 2.5rem;
}
.web .web-text .center-title {
    width: 20.6vw;
    height: 100px;
    margin: auto;
    text-align: center;
    display: flex;
    flex-direction: column;
    white-space: nowrap;
    color: rgba(0, 43, 125, 0.76);
    font-family: 思源黑体;
    font-size: 1.5rem;
    font-weight: 700;
    line-height: 2.1875rem;
    letter-spacing: -0.1875rem;
    text-align: left;
}

.web .web-center {
    display: flex;
}
.web .web-center .web-left {
    width: 18.8vw;
    height: 659px;
    border-bottom: 1px solid rgba(184, 183, 183, 0.09);
    border-left: 1px solid rgba(184, 183, 183, 0.09);
    border-right: 1px solid rgba(184, 183, 183, 0.09);
    border-radius: 120px 120px 120px 0px;
    box-shadow: 0px 4px 5px 0px rgba(0, 0, 0, 0.1);
    background: rgb(255, 255, 255);
    display: flex;
    flex-direction: column;
    justify-content: space-around; /* 两个盒子分布在两端 */
}
.web .web-center .web-left .navigation {
    width: 20.6vw;
    height: 85px;
    border-radius: 0px 50px 50px 0px;
    background: white;
    font-size: 20px;
    transition: background-color 0.3s; /* 添加背景颜色过渡效果 */
    cursor: pointer;
}

.web .web-center .web-left .navigation:nth-child(2) {
    background: rgb(170, 215, 239);
}

.web .web-center .web-text .web-passenger {
    width: 72vw;
    height: 200px;
    display: flex;
    flex-direction: row;
}
.web .web-center .web-text .web-passenger .web-passenger-image {
    height: 173px;
    width: 33vw;
    padding: 10px;
    background-image: url(@/assets/images/image.png);
    background-size: cover;
    background-repeat: no-repeat;
}
.web .web-center .web-text .web-passenger .web-passenger-text {
    height: 173px;
    width: 38.6vw;
    background-size: cover;
    background-repeat: no-repeat;
}
.web
    .web-center
    .web-text
    .web-passenger
    .web-passenger-text
    .web-passenger-text1 {
    width: 100%;
    height: 1.25rem;
}

.web .web-center .web-text .web-passenger-product {
    width: 100%;
    height: 305px;
    display: flex;
    justify-content: center; /* 水平居中子元素 */
    align-items: center; /* 垂直居中子元素（可选） */
    box-sizing: border-box;
    border: 0.0625rem solid rgba(0, 0, 0, 0.24);
    background: rgb(255, 255, 255);
}
.web .web-center .web-text .web-passenger-product .web-passenger-product-box {
    width: 96vw;
    height: 90%;
    display: flex;
    flex-direction: row;
}
.web
    .web-center
    .web-text
    .web-passenger-product
    .web-passenger-product-box
    .web-passenger-product-box-img {
    width: 45vw;
    height: 100%vh;
    background-image: url(@/assets/images/image.png);
    background-size: cover;
    background-repeat: no-repeat;
}
.web
    .web-center
    .web-text
    .web-passenger-product
    .web-passenger-product-box
    .web-passenger-product-box-text {
    width: 50%;
    height: 100%;
    background: white;
    margin: auto;
    color: rgb(0, 80, 165);
    font-family: 思源黑体;
    font-size: 1.5rem;
    font-weight: 400;
    line-height: 2.1875rem;
    letter-spacing: 0rem;
    text-align: left;
}

.web
    .web-center
    .web-text
    .web-passenger-product
    .web-passenger-product-box
    .web-passenger-product-box-text
    .web-passenger-product-box-text-bottom {
    width: 100%;
    height: 2.8125rem;
    bottom: 0;
    margin-top: 2.8125rem; /* 将子盒子推到容器的底部 */
}
.web
    .web-center
    .web-text
    .web-passenger-product
    .web-passenger-product-box
    .web-passenger-product-box-text
    .web-passenger-product-box-text-bottom
    .button-link {
    display: inline-block;
    width: 18.2667vw;
    height: 2.5rem;
    color: white;
    text-decoration: none;
    border-radius: 3.125rem;
    background: rgb(170, 215, 239);
    border: none;
    cursor: pointer;
    color: rgb(0, 0, 0);
    font-family: 思源黑体;
    font-size: 1.25rem;
    font-weight: 400;
    line-height: 1.8125rem;
    letter-spacing: 0rem;
    text-align: left;
}
/* 字体 */
.chinese {
    color: rgba(0, 43, 125, 0.85);
    font-family: 思源黑体;
    font-size: 1.625rem;
    font-weight: 700;
    line-height: 2.375rem;
    letter-spacing: -0.1875rem;
    text-align: left;
}
.english {
    color: rgba(0, 43, 125, 0.85);
    font-family: 思源黑体;
    font-size: 0.875rem;
    font-weight: 400;
    line-height: 1.25rem;
    letter-spacing: 0rem;
    text-align: left;
}
.text3 {
    color: rgba(117, 171, 227, 0.87);
    font-family: 思源黑体;
    font-size: 1.125rem;
    font-weight: 700;
    line-height: 1.625rem;
    letter-spacing: 0rem;
    text-align: left;
}
.text4 {
    color: rgb(0, 43, 125);
    font-family: 思源黑体;
    font-size: 1.75rem;
    font-weight: 400;
    line-height: 2.5625rem;
    letter-spacing: 0rem;
    text-align: left;
}
.text5 {
    color: rgb(0, 80, 165);
    font-family: 思源黑体;
    font-size: 1.5rem;
    font-weight: 400;
    line-height: 2.1875rem;
    letter-spacing: 0rem;
    text-align: left;
}
.text6 {
    color: rgba(0, 43, 125, 0.85);
    font-family: 思源黑体;
    font-size: 1.25rem;
    font-weight: 700;
    line-height: 1.8125rem;
    letter-spacing: 0rem;
    text-align: left;
}
.text7 {
    color: rgba(0, 43, 125, 0.85);
    font-family: 思源黑体;
    font-size: 0.75rem;
    font-weight: 400;
    line-height: 1.0625rem;
    letter-spacing: 0rem;
    text-align: left;
}
/* 添加高亮效果的样式 */
.navigation .active {
    transition: background-color 0.3s; /* 平滑过渡效果 */
    background: rgb(170, 215, 239);
}
</style>
