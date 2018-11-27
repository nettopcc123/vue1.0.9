<template>
    <div>
        <div class="iftop">
        <div class="ifhidl"></div>
        <div class="ifhidr"></div>
        <iframe ref="iframe" id="bdIframe" :src="bdTokenUrl" frameborder="0" scrolling="no" width="100%" height="100%" ></iframe>
        </div>
    </div>
</template>

<script>
//http://sports.qq.com/kbsweb/kbsshare/gamelist.htm?#nav-laliga
    export default {
        data() {
            return {
                bdTokenUrl: 'http://m.188bifen.com/' //https://m.sporttery.cn/app/zf/fb/livelist.html  https://m.sporttery.cn/app/zf/fb/livelist.html http://www.yidianzixun.com/#/?id=c2&name=%E4%BD%93%E8%82%B2
            }
        },
        // created() {
        //     this.getUrl();
        //     this.$nextTick(()=>{
        //         this.getCode();
        //     });
        // },
        mounted(){
            /**
             * iframe-宽高自适应显示   
             */
            const oIframe = document.getElementById('bdIframe');
            const deviceWidth = document.documentElement.clientWidth;
            const deviceHeight = document.documentElement.clientHeight;
            oIframe.style.width =  '100%'; //数字是页面布局宽度差值
            oIframe.style.height = '100%'; //数字是页面布局高度差
        }
    }
</script>

<style lang="scss" scoped>
@import "scss/base.scss";
.child-view{
    height:100%;
}
.iftop{
    height: 100%;
    margin-top:0.08rem;
}
.ifhidr{
    background:#fff;
    height: 0.38rem;
    width: 0.92rem;
    position: absolute;
    right: 0px;
    top:0.41rem;
}
.ifhidl{
    background:#fff;
    height: 0.38rem;
    width: 0.81rem;
    position: absolute;
    left: 0px;
    top:0.41rem;
}
</style>
