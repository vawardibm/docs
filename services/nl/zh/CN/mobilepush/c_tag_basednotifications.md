---

标题：启用基于标记的推送通知

关键字：基于标记的推送通知, 定义标记, tagName
copyright:
 years: 2015, 2016

---

# 启用基于标记的通知
{: #tag_based_notifications}
*上次更新时间：2016 年 7 月 13 日*
{: .last-updated}

基于标记的通知消息是针对预订了特定标记的所有设备的通知消息。您可以定义标记，然后使用标记发送和接收消息。必须首先为应用程序创建标记，设置标记预订，然后再启动基于标记的通知。要使用 [REST API](https://mobile.{DomainName}/imfpushrestapidocs/){: new_window} 发送基于标记的通知，请确保发布到消息资源时提供了“tagName”。
