<!--
 * @Author: sheep669
 * @Description: 产品分类模块
 * @Date: 2022-8-22 16:03:54
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="goods_classification">
        <div
            class="right"
            style="
                height: 100%;
                width: calc(100% - 160px);
                float: right;
                overflow-y: auto;
            "
        >
            <el-card shadow="always" body-style="0px" style="margin: 8px">
                <!-- <emo-table /> -->
                <!-- <emo-pagination style="margin-top: 15px" /> -->
                goods_classification page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "GoodsClassification",
};
</script>
<style lang='less' scoped>
</style>