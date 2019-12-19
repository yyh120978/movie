<template>
    <div>
        <el-row><h1 style="margin-top: 30px;text-align: left">豆瓣电影排行榜</h1>
            <div style="text-align: left"><h3 style="color: #058304">豆瓣新片榜· · · · · ·</h3></div>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
            <img src="../assets/1.jpg" style="width: 150px; height: 200px">
        </el-col>
                <el-col :span="8" style="text-align: justify">
               <div style="margin-top: 20px; color: #466ba9">小丑/小丑起源电影：罗密欧/Romeo</div>
                    <div style="margin-top: 20px;color: #5d5d5d">2019-08-31(威尼斯电影节) / 2019-10-04(美国) / 杰昆·菲尼克斯 / 罗伯特·德尼罗 / 马克·马龙 / 莎姬·贝兹 / 谢伊·惠格姆 / 弗兰西丝·康罗伊 / 布莱恩·考伦 / 布莱恩·泰里·亨利 / 布莱特·卡伦 / 道格拉斯·霍奇斯 / 格伦·弗莱施勒 / 比尔·坎普...
                    </div>
                    <div style="margin-top: 25px;">
                        <el-rate
                                v-model="value5"
                                disabled
                                text-color="#ff9900"
                                text-template="{value}">
                        </el-rate>
                    </div>
                    <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.8</a>  &nbsp;(123358人评价)</div>
            </el-col>
        </el-row>
    <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/10.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">地久天长</div>
                <div style="margin-top: 20px;color: #5d5d5d">中国 / 动作  / 剧情 / 家庭 / 126分钟/
                    王景春 / 咏梅 / 齐溪 / 王源 / 杜江 / 艾丽娅 / 徐程 / 李菁菁 / 赵燕国彰
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.7</a>  &nbsp;(2354563人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/7.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">攀登者</div>
                <div style="margin-top: 20px;color: #5d5d5d">中国大陆 / 剧情 / 爱情 / 冒险 / 117分钟/
                    吴京 / 章子怡 / 井柏然 / 张译 / 胡歌 / 成龙 / 陈龙 / 多布杰 / 何琳 / 刘小锋 / 拉旺罗布 / 曲尼次仁 / 王景春
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.9</a>  &nbsp;(45358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/6.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">爱尔兰人/The Irishman(2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">美国 / 剧情 / 传记 / 犯罪 /210分钟/
                    罗伯特·德尼罗 / 阿尔·帕西诺 / 乔·佩西 / 安娜·帕奎因 / 杰西·普莱蒙 / 哈威·凯特尔 / 斯蒂芬·格拉汉姆 / 鲍比·坎纳瓦尔 / 杰克·休斯顿 / 阿莱卡萨·帕拉迪诺~~
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.0</a>  &nbsp;(3358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/5.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">酷刑报告</div>
                <div style="margin-top: 20px;color: #5d5d5d">美国/剧情/悬疑/等/ 118分钟/
                    亚当·德赖弗 / 寇瑞·斯托尔 / 小伊万德·杜克 / 乔恩·哈姆 / 琳达·鲍威尔 / 安妮特·贝宁 / 桑德拉·兰德斯 / 约翰·罗斯曼 / 维克多·斯勒扎克 / 盖伊·博伊德~~
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.2</a>  &nbsp;(6358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/8.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">准备好了没/Ready or Not (2019)</div>
                <div style="margin-top: 20px;color: #5d5d5d">加拿大 / 美国/悬疑 / 惊悚 / 恐怖 / 95分钟
                    萨玛拉·维文 / 安迪·麦克道威尔 / 马克·奥布莱恩 / 亚当·布罗迪 / 亨利·科泽尼 / 妮基·瓜达尼 /
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">9.1</a>  &nbsp;(8358人评价)</div>
            </el-col>
        </el-row>
        <hr/>
        <el-row>
            <el-col :span="4">
                <img src="../assets/3.jpg" style="width: 150px; height: 200px">
            </el-col>
            <el-col :span="8" style="text-align: justify">
                <div style="margin-top: 20px; color: #466ba9">非凡夏日2019</div>
                <div style="margin-top: 20px;color: #5d5d5d"> 荷兰 / 德国/ 家庭/82分钟/
                    桑尼·库普斯·范·乌特伦 / 约瑟芬·阿伦森 / 特伯·格里兹玛 / 珍妮弗·霍夫曼 / 朱利安·拉斯 /~~
                </div>
                <div style="margin-top: 25px;">
                    <el-rate
                            v-model="value5"
                            disabled
                            text-color="#ff9900"
                            text-template="{value}">
                    </el-rate>
                </div>
                <div style="margin-top: -20px;margin-left: 120px"><a style="color: #b88b1f">8.1</a>  &nbsp;(23358人评价)</div>
            </el-col>
        </el-row>
    </div>
</template>
<script>
    import ElRow from "element-ui/packages/row/src/row";
    export default {
        components: {ElRow},
        data() {
            return {
                value5:3.0
            }
        }
    }
</script>
