<!--
 * @Author: sheep669
 * @Description: 待提货模块
 * @Date: 2022-8-22 15:38:08
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="wait_receive_orders">
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
                wait_receive_orders page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "WaitReceiveOrders",
};
</script>
<style lang='less' scoped>
</style>