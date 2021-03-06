# 短信补充服务
<style>
img[alt=jpush_ios_v] { width: 500px; }
img[alt=jpush_android_so] { width: 800px; }
</style>
<br/>
<br/>
针对开发者提供推送补充服务，如果 App 侧一段时间内无法收到推送的消息（可能由于断网、后台禁止运行、消息延迟等原因）的用户进行短信通道信息补充。对于到达强需求的业务优先使用推送可以一定程度减少短信费用开销，又能保证信息最终的传递到达。

## 优势
极光推送的短信服务有如下优势:  

+ 独享通道：享有独立通道，高速稳定；  
+ 三网合一：目前支持中国移动，中国联通，中国电信三大运营商的手机用户，短信推送及时准确送达。（暂不支持国外的手机号）  
+ 极速稳定：极光千台服务器强力支持，覆盖范围广，极致提升短信推送效率；  
+ 低成本：发送短信的费用低；  
+ 灵活性：模板与模式可随心定制。


## 数据指标
下发速度：与运营商合作，下发速度 200 条/秒；  
送达时间：送达时间由运营商控制，一般情况下是几秒送达；  
短信内容：内容要求符合国家规定，正常的营销信息可正常发送，手机用户可以选择是否接收。


## 充值与开通
短信价格按照月消费数量会有所不同，详细价目表请咨询商务。  
如果您想开通短信服务，请向商务提供相关登记信息，并预存费用至极光推送的账户即可开通。  
[联系商务开通服务](https://www.jiguang.cn/accounts/business_contact?fromPage=push_doc)


## 使用指南
目前仅有 API 形式提供服务。原有 App 推送功能不变，仅是新增了短信接口。

参考文档：[服务器端-sms_message](../server/push/rest_api_v3_push/#sms_message)




