<script setup lang="ts">
import { onMounted } from 'vue'
import { info } from '../../scripts/stat-api'

onMounted(() => {
  info()
})
</script>

# 成为 Blossom 的赞助者 🤝

<br/>
<br/>
<bl-img src="../../imgs/logo/logo.svg" width="150px" :shadow="false" :drop-shadow="true"/>

你好！我是 Blossom 笔记软件的作者，是一名正在探索中的全职独立开发者，你可以叫我小贼。

Blossom 是一个 MIT 协议开源的笔记软件。MIT 是一个非常宽松的协议，意味着你可以随意使用该应用，修改源代码，或者通过该应用进行商业活动。

---

**Blossom 不会向你收取任何的费用，你可以永久免费使用！**

但该项目设计，开发，测试需要大量的时间和精力，作为个人开发者不得不寻找一些其他方式来维持生活，如果你愿意赞助我的工作，将非常有助于该项目的成长，并激励我长期持续下去！

作为赞助者，你的名字将出现在 Blossom 的 README 中，

<div class="sponsor">
  <div class="item">
    <bl-img src="../../imgs/blossom/wechat.png" />
    <div class="name">微信</div>
  </div>

  <div class="item">
    <bl-img src="../../imgs/blossom/ali.png" />
    <div class="name">支付宝</div>
  </div>
  
  <div class="item">
    <bl-img src="../../imgs/blossom/aifadian.png" />
    <div class="name">爱发电</div>
  </div>
</div>

<style scoped>
.sponsor {
  display:flex;flex-direction: row;justify-content: space-around;overflow:scroll;
  padding: 10px;
  margin-bottom:20px;
}

.sponsor .item {
  min-width:30%;
  margin-right:10px;
}

.sponsor .item .name {
  width: 100%;
  font-size: 18px;
  color: #9E9E9E;
  text-align: center;
  margin-top: 10px;
}
</style>