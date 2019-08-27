<template>
  <view class="content">
    <view class="main">
        <view class="erwm"> 
            <image src="http://www.ehsure.com/shysxx201805182332/uploadfiles/2018/08/20180814133921108.png"></image>
        </view>
    <view class="bottom">
        <view class="left"></view>
        <view class="center">
            <image src="/static/img/tuo.png"></image>
        </view>
        <view class="right"></view>
    </view>
    <view class="footer">
        <view class="one">塔利亚</view>
        <view class="two">扫一扫二维码图案，关注我吧</view>
    </view>
    
   
    
    </view>
   
  </view>
</template>
<style lang="less" scoped>
.content {
  width: 100vw;
  height: 177.87vw;
  background-color: #f6f6f8;
  padding-top: 10.8vw;
  .main {
    width: 73.33vw;
    height: 94.67vw;
    background-color: #fff;
    margin: 0 auto;
    display: flex;
    flex-direction: column;
    align-items: center;
    
    .erwm{
        width: 38.4vw;
        height: 38.27vw;
        margin-top: 8vw;
        image{
            width: 38.4vw;
            height: 38.27vw;
        }
    }
     .bottom{
         width:73.33vw;
         height: 17vw; 
         background-color: #fff;
         display: flex;
         flex-direction: row;
         justify-content: center;
         align-items: center;
         
         
          .left{
                width:21vw;
                height:1px;
                background-color: #C0C4CC;
             }
         .center{
             width: 17vw;
             height: 17vw;
             image{
                 width: 17vw;
                 height: 17vw;
                 border-radius: 50%;
             }
             padding-left: 3vw;
             padding-right: 3vw;
         }
         .right{
              width:21vw;
              height:1px;
              background-color: #C0C4CC;
         }
     }
     .footer{
         display: flex;
         flex-direction: column;
         align-items: center;
         margin-top: 2vw;
        .one{
         font-size:5vw;
         font-family:PingFangSC;
         font-weight:500;
         color:rgba(51,51,51,1);     
     }
     .two{
         font-size:3vw;
         font-family:PingFangSC;
         font-weight:400;
         color:rgba(144,147,153,1);
         margin-top: 1vw;    
     }
     }
         
       
     
   
  }
 
}
</style>