<!--
 * @Author: sheep669
 * @Description: 黑名单模块
 * @Date: 2022-8-22 15:38:08
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="black_list">
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
                black_list page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "BlackList",
};
</script>
<style lang='less' scoped>
</style>