<!--
 * @Author: sheep669
 * @Description: 商品标签模块
 * @Date: 2022-8-22 16:03:54
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="goods_label">
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
                goods_label page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "GoodsLabel",
};
</script>
<style lang='less' scoped>
</style>