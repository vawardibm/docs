---

copyright:
 years: 2015, 2016

---

# 通知の使用可能化
{: #c_enable_push-notifications}
*最終更新日: 2016 年 6 月 14 日*
{: .last-updated}

アプリケーションでプッシュ通知を受け取り、デバイスにプッシュ通知を送信できるようにすることができます。

このセクションでは、モバイル・アプリケーションでのプッシュ通知の受け取りを可能にする方法、基本通知の作成方法、SDK またはプラグインの取得と初期化の方法、およびプッシュ通知を受け取るためにデバイスを登録する方法について説明します。また、ご使用のモバイル・アプリケーションで [REST API](t_restapi.html) を使用してプッシュ通知を受け取れるようにすることもできます。

注: プッシュ通知サービスは、プッシュへのデバイス登録のために、通知プロバイダー (Apple の APNS または Google の GCM) から発行されたトークンに対する固有の参照を維持します。これらのトークンは、いくつかの理由で、プッシュ通知サービスの通知プロバイダーによって無効にされることがあります。 

例えば、デバイス上のアプリケーションのアンインストール時について考えてみます。この場合、そのデバイスが無効にされているプロバイダーの応答に基づいて通知を配信しようとすると、プッシュ通知サービスはそのデバイス登録を削除します。その結果として、これらの無効にされたデバイスに通知を送信しようとする試みが抑えられることになります。
