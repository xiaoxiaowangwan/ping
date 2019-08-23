<template>
    <view class="page">
        <view>
             <slot />
            123
            <image src="../../static/icon/fudai.png"></image> 
        </view>
    </view>
</template>
<script>
export default {
    name:"divDiv",
    props:{
       content:{
           type: String
       }
    },
    data(){
        return{

        }
    }
}
</script>

<style lang="less" scoped>
.page{
    width:100%;
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: center;
}
</style>

