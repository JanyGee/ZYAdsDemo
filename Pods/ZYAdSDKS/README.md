1.5.3-------------------------20200609
1，升级 'GDTMobSDK','4.11.8'

1.5.2-------------------------20200429
1，config加载逻辑优化
2，统计log出错缓存条数限制
3，增加isShowing逻辑，防止show的时候加载bug
4，MintegralAdSDK兼容新增板块id配置，升级到6.1.3.0
6，升级 'GDTMobSDK','4.11.7'
7，升级 'Google-Mobile-Ads-SDK','7.58.0'

1.5.1-------------------------20200407
1，升级穿山甲2.9.5.0，优化107渲染超时问题
2，升级facebook5.7.1
3，新增Mintegral广告6.1.2.0

依赖：
ZYCoreKits 1.3.2

1.5.0-------------------------20200327
1，缓存优化
2，错误码优化
3，升级AppLovinSDK 6.11.6
4，升级IronSourceSDK 6.15.0.1
5，升级VungleSDK-iOS 6.5.3
6，升级Bytedance-UnionAD 2.9.0.1
7，升级Google-Mobile-Ads-SDK 7.57.0
8，升级AppsFlyerFramework 5.2.0
依赖：
ZYCoreKits 1.3.2

1.4.9-------------------------20200319
1，新增Sigmob广告平台，2.16.0
2，新增广点通广告平台，4.11.5
3，头条渲染成功回调adDidLoad
依赖：
ZYCoreKits 1.3.2

1.4.8-------------------------20200228
1，升级头条 pod 'Bytedance-UnionAD', '2.8.0.1'
2，升级admob pod 'Google-Mobile-Ads-SDK', '7.55.1'
3，升级Unity pod 'UnityAds', '3.4.2'
4，升级ironsource pod 'IronSourceSDK','6.14.0.0'
5，升级vungle pod 'VungleSDK-iOS', '6.5.2'
6, 集成AppLovin 广告 banner、rewardedVideo，pod 'AppLovinSDK', '6.11.3'
7, 重复load广告控制
8, 第三方广告SDK Version log
依赖：
ZYCoreKits 1.3.2

1.4.7-------------------------20200103
1，升级头条 pod 'Bytedance-UnionAD', '2.5.1.5'
2，升级admob pod 'Google-Mobile-Ads-SDK', '7.53.0'
3，升级Unity pod 'UnityAds', '3.4.0'
4，升级facebook pod 'FacebookAdsSDK', '5.6.0'
5，升级ironsource pod 'IronSourceSDK','6.11.0.0'
6，升级vungle pod 'VungleSDK-iOS', '6.4.6'
依赖：
ZYCoreKits 1.3.2

1.4.6-------------------------201901206
1，头条fullscreenVideo更新为模板渲染
2，头条rewardedVideo更新为模板渲染
3，无网切换到有网配置加载优化
4，解决广告互换bug
依赖：
ZYCoreKits 1.3.1

1.4.5-------------------------201901119
1，升级头条 pod 'Bytedance-UnionAD', '2.5.1.2'
2，头条插屏适配iPad
3，增加banner自动刷新开关

依赖：
ZYCoreKits 1.3.1

1.4.3-------------------------201901014
1，升级UM pod 'UMCAnalyticsGame','6.0.5+G'
2，升级AppsFlyer pod 'AppsFlyerFramework','4.10.4'
3，升级头条 pod 'Bytedance-UnionAD', '2.4.6.7'
4，升级Unity pod 'UnityAds', '3.3.0'
5，升级IronSource pod 'IronSourceSDK','6.8.7.0'
6，升级Vungle pod 'VungleSDK-iOS', '6.4.5'
依赖：
ZYCoreKits 1.3.0

1.4.2-------------------------20190925
1，适配iOS13
2，升级广告：
#toutiao
pod 'Bytedance-UnionAD', '2.4.6.3'
##admob
pod 'Google-Mobile-Ads-SDK', '7.50.0'
##facebook
pod 'FacebookAdsSDK', '5.5.0'
##ironsource
pod 'IronSourceSDK','6.8.5.0'
##vungle：
pod 'VungleSDK-iOS', '6.4.3'
依赖：
ZYCoreKits 1.3.0


1.4.1-------------------------20190920
1，新增UMPush
2，友盟和AppsFlyer接口优化
依赖：
ZYCoreKits 1.3.0

1.4.0-------------------------20190910
1,新增DataAnalytics
2,配置分段加载
3，友盟用游戏统计SDK 'UMCAnalyticsGame','6.0.3+G'
依赖：
ZYCoreKits 1.3.0

1.3.0-------------------------20190801
1，新增ZYDataAnalytics（test）
2，interstitial，fullscreenVideo，rewardedVideo展示后自动加载最新广告
3，审核处理，关闭渠道初始化失败
4，max_impressions控制
5, adControl debug
6，升级广告
头条
pod 'Bytedance-UnionAD', '2.2.0.2'
admob
pod 'Google-Mobile-Ads-SDK', '7.48.0'
unity
pod 'UnityAds', '3.2.0'
ironsource
pod 'IronSourceSDK','6.8.4.2'
依赖：
demo 1.3.0
ZYCoreKits 1.3.0

1.2.0-------------------------20190726
1，新增统计
pod 'AppsFlyerFramework','4.10.0'
2，config，geo数据用fmdb缓存
3，ZYAdSDK.bundle 增加 PrivacyAgreement.html
依赖：
demo 1.2.0
ZYCoreKits 1.2.0

1.1-------------------------20190711
1，新增
ironsource 6.8.3.0
vungle 6.3.2
2，新增ip请求，ad_ip支持区域识别
3，欧盟地区支持gdpr协议
依赖：
demo 1.1
ZYCoreKits 1.1

1.0-------------------------20190620
支持按广告价格和优先级加载广告
支持平台：头条，admob，facebook，unity
依赖：
demo 1.0
ZYCoreKits 1.0
