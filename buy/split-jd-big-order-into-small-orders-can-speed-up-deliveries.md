# 京东大订单显示某些商品缺货，等待采购。但是申诉后拆分小订单后却不再缺货可以快速送货

## 问题
* 有多个京东自营商品（比如得力文具京东自营旗舰店），在商品详情页面，明确有货，且可以在同一天送达
* 支付后，提示 1 个订单需要等待采购完毕一起送货，没有具体送达时间
* 联系商品对应的客服（得力京东自营客服），回答某个商品缺货

## 原因
* 商品在详情页面显示有货，支付后没货，因为是不同的仓库发货
  * A 商品在 仓库 1 有货
  * B, C 商品在 仓库 2 有货
  * 同时下单 A, B, C 时，可能就从仓库 2 发货，B, C 需要等待 A 从 仓库 1 调货完成后一起配送

## 解决
* 通过 我的 > 客户服务 > 底部的我的客户经理，说明情况后
* 将大订单拆分成小订单，结果每个小订单都显示有货，显示明确送达时间
 