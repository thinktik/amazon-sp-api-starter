## 我的公司有在Amazon上有多个店铺，这些店铺的营业执照不同；现在我用A店铺的营业职照申请了SP-API开发者账户，那么这个开发者账户可以获取B店铺的数据么？

一般而言是不行的，如果你使用A店铺的执照申请了一个SP-API开发者账户，那么要看你是什么类型的才能确定是否可以获取B店铺的数据：
1. 如果你申请到的是[私有 SP-API 开发者](https://developer-docs.amazon.com/sp-api/lang-zh_CN/docs/register-as-a-private-developer),那么这个SP-API开发者账户只能看到A店铺的数据，看不到B店铺的数据。因为私人开发者只能看到自己本店铺的数据。私有 SP-API 开发者账户一般适合店铺自用。
2. 如果你申请到的是[公共 SP-API 开发者](https://developer-docs.amazon.com/sp-api/lang-zh_CN/docs/register-as-a-public-developer),那么你在B店铺的授权下，是可以看到A、B店铺的数据的。公共 SP-API 开发者账户一般适合SaaS服务商使用。

详情请见：[SP-API 注册概览](https://developer-docs.amazon.com/sp-api/lang-zh_CN/docs/sp-api-registration-overview)


## 我的公司有在Amazon上有多个店铺，这些店铺的营业执照不同；现在A店铺的SP-API申请过了，但是B、C店铺的SP-API的申请过不了，这会影响A店铺的的SP-API开发者权限么？

不影响已经通过的SP-API申请的A店铺的开发者账户的正常使用。B、C店铺申请不过，一般是你申请资料和A店铺高度雷同，有一定申请资料合法性的嫌疑，导致了B、C店铺的申请被拒绝。你需要填写的设计自己B、C店铺的资料，不要简单的复制粘贴以前A店铺的资料！