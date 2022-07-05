<!--
 * @Author: sheep669
 * @Description: 会员标签模块
 * @Date: 2022-7-5 16:45:37
-->
<template>
    <!-- suggest to replace '_'===> '-' -->
    <div id="user_label">
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
                user_label page
            </el-card>
        </div>
    </div>
</template>
<script>
export default {
    name: "UserLabel",
};
</script>
<style lang='less' scoped>
</style>