<template>
    <div>
        <van-tabbar v-model="active">
            <van-tabbar-item icon="home-o">外面</van-tabbar-item>
            <van-tabbar-item icon="search">搜索</van-tabbar-item>
            <van-tabbar-item icon="friends-o">订单</van-tabbar-item>
            <van-tabbar-item icon="contact">我的</van-tabbar-item>
        </van-tabbar>
    </div>
</template>
<script>
export default {
    name:"home",
    data(){
        return{
            active:0,
        }
    }
}
</script>