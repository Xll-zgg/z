<template>
  <div id="app">
    <!-- <van-nav-bar left-text="搜索" title="定位中..." right-text="登录|注册" left-arrow @click-left="onClickLeft" @click-right="onClickRight"/> -->
    <van-nav-bar title="定位中..." right-text="登录|注册" left-arrow class="vannavbar">
      <template #left>
        <van-icon name="search" size="18" />
      </template>
    </van-nav-bar>
    <div>
      <van-swipe class="my-swipe" :autoplay="3000" indicator-color="white">
        <van-swipe-item>
          <van-grid :column-num="4">
            <van-grid-item icon="gift" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
          </van-grid>
          <van-grid :column-num="4">
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
          </van-grid>
        </van-swipe-item>
        <van-swipe-item>
          <van-grid :column-num="4">
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
          </van-grid>
          <van-grid :column-num="4">
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
            <van-grid-item icon="photo-o" text="文字" />
          </van-grid>
        </van-swipe-item>
        <van-swipe-item>3</van-swipe-item>
        <van-swipe-item>4</van-swipe-item>
      </van-swipe>
    </div>
    <div>
      <p>附件商家</p>
      <van-card num="2" price="2.00" desc="描述信息" title="商品标题" thumb="https://img01.yzcdn.cn/vant/ipad.jpeg"/><hr>
      <van-card num="2" price="2.00" desc="描述信息" title="商品标题" thumb="https://img01.yzcdn.cn/vant/ipad.jpeg"/>
      <van-card num="2" price="2.00" desc="描述信息" title="商品标题" thumb="https://img01.yzcdn.cn/vant/ipad.jpeg"/>
      <van-card num="2" price="2.00" desc="描述信息" title="商品标题" thumb="https://img01.yzcdn.cn/vant/ipad.jpeg"/>
    </div>
    <router-view></router-view> 
  </div>
</template>

<script>
import { Toast } from 'vant';

export default {
};
</script>
<style>
  .vannavbar {
    background-color: #00A67C;
  }
  .my-swipe .van-swipe-item {
    color: #fff;
    font-size: 20px;
    line-height: 150px;
    text-align: center;
    background-color: #39a9ed;
  }
</style>

