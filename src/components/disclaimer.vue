<template>
<div id="disclaimer">
 <h2 class="uitit_a fmt30">免责声明</h2>
 <div class="disw">
      <p class="discon">
      任何人访问、浏览天彩，即承认已阅读、理解并同意受本使用条款约束，并遵守所有适用的法律和法规。
      若您不同意遵从本使用条款，请勿访问天彩。天彩有权随时更新本使用条款，您将受到更新后的使用条款的约束，因此您应经常了解本网站的使用条款。
      </p>
      <h4 class="distit">一、版权归属</h4>
      <p class="discon">
            本网站提供的任何内容（包括但不限于数据、文字、图表、图象、声音、录像、软件等）的版权均属于天彩或相关权利人。
            未经天彩或相关权利人事先的书面许可，您不得以任何方式擅自复制、再造、传播、出版、转帖、改编或陈列本网站的内容。
            同时，未经天彩书面许可，对于本网站上的任何内容，任何人不得在非天彩所属的服务器上做镜像。
            任何未经授权使用本网站的行为都将违反《中华人民共和国著作权法》和其它法律法规以及有关国际公约的规定。
      </p>
      <h4 class="distit">二、不担保声明</h4>
      <p class="discon">
            天彩不能保证本网站上任何内容的正确性、及时性、完整性和可靠性以及使用这些内容得出的结果。天彩以及其员工、
            代理以及其他任何代表（以下简称“相关人”）对于本网站内容的任何错误、不准确和遗漏以及使用本网站内容得出的结果都将不承担任何责任。
            天彩及相关人不能保证您任何时候均可进入、浏览和使用本网站，对本网站和其内容的不能使用和使用错误不承担任何责任。
      本网站上所有彩票软件属于对彩票的分析辅助工具，彩票软件提供的数据仅作参考，不作为保证软件用户中奖的依据、承诺。
      </p>
      <h4 class="distit">三、免责声明</h4>
      <p class="discon">
            任何情况下，天彩及相关人对于进入或使用本网站引起的任何依赖本网站内容而作出的决定或采取的行动不承担任何责任，
            对进入或使用本网站软件产品而产生的任何直接的、间接的、惩罚性的损失或其他任何形式的损失包括但不限于业务中断、
            数据丢失或利润损失不承担任何责任，即使天彩被明确告知可能会发生上述损失。
            天彩以及相关人对于您在进入、浏览和使用本网站或从本网站下载任何内容而导致病毒或其他破坏性程序对您的电脑系统以及其他任何软件、
            硬件、IT系统或财产的损害或损失不承担任何责任。天彩以及相关人对于第三人采用非法手段进入本网站取得有关密码、资料和内容而造成的任何损害或损失不承担任何责任
      </p>
      </div> 
 </div>
 </template>
<script>
export default {
  name:'disclaimer',
  methods:{

  }
}
</script>

<style lang="scss" scoped>
@import "scss/base.scss";
.disw{
      padding:0.05rem 0.1rem
}
.discon{
      display: block;
      line-height: 0.22rem;
      color:#575757
}
.distit{
      display: block;
      line-height: 0.26rem; 
      margin-top:0.1rem;  
}
.uitit{
    display: block;
    line-height: 0.36rem!important;
    border-left: 0.03rem solid $bgColor!important;
    padding-left:0.15rem;
    font-size: 0.18rem;
    text-align: left;
    background:#fff!important;
}
.uitit_a{
    display: block;
    line-height: 0.36rem!important;
    padding-left:0.15rem;
    font-size: 0.18rem;
    text-align: center;
    background:#f1efef !important;
    border-bottom: 1px solid #fff;
    color:#404040;
    font-weight: normal;
}
.fmt30{
  margin-top:0.4rem;
}
</style>