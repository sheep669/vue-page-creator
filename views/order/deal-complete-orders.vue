<!--
 * @Author: sheep669
 * @Description: 交易完成模块
 * @Date: 2022-7-5 16:45:37
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="deal_complete_orders">
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
                deal_complete_orders page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "DealCompleteOrders",
};
</script>
<style lang='less' scoped>
</style>