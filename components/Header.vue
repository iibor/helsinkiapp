<template>
    <view class="header">
        <text class="title">{{ title }}</text>
    </view>
</template>

<script>
export default {
    props: ['title']
}
</script>

<style>
.header {
    height: 60px;
    background-color:#0000bf;
    justify-content: center;
    align-items: center;
}
.title {
    color: #F3F3F3;
    font-size: 28px;
    font-weight: 900;
    text-transform: lowercase;
}
</style>