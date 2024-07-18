# Ads
## [TikTok Creative Center](https://ads.tiktok.com/business/creativecenter/pc/en?rid=vcxdlcdh10o)
- [About TikTok Ads Manager](https://ads.tiktok.com/help/article/tiktok-ads-manager-intro?lang=en)
  * **Dashboard**: Allows you to track changes in performance and review ad account data such as active campaigns, budget spending, and charts for tracking ad performance over time.
  * **Campaign**: Review all campaigns, ad groups, and ads you have created.
  * **Tools**: You can choose from 6 options in the drop-down list to manage what goes into your ads and who you want to reach: Events, Creatives, Audiences, Catalogs, Comments, and Instant Pages.
  * **Analytics**: You can create custom reports, or use one of our reporting templates to go deeper into your ad insights. You can also schedule reports to generate at a specific time.

 - [Ads Manager Walk Through]
   * Create a campaign by objectives 
    <img width="929" alt="Screenshot 2024-07-18 at 3 25 39 PM" src="https://github.com/user-attachments/assets/579dc9d2-6238-4df9-aa6f-039f9aa6e7a2">

   * Automated rules in Tools
    <img width="946" alt="Screenshot 2024-07-18 at 3 29 19 PM" src="https://github.com/user-attachments/assets/dcebcb93-c586-445b-b28e-94aa55a532aa">

   * Under [Analytics](https://ads.tiktok.com/i18n/audience-insight?aadvid=7393058749373546497)
    <img width="959" alt="Screenshot 2024-07-18 at 3 31 04 PM" src="https://github.com/user-attachments/assets/84ed57c3-5137-49bc-b2b0-f56b3b39f348">

    
## [16 of the Best TikTok Tools to Improve Your Marketing](https://blog.hootsuite.com/tiktok-tools/)
## [广告创建与投放](https://school.oceanengine.com/product_help/content/668400000006/121544)
## [抖音广告设计与推送算法](https://www.admin5.com/article/20201110/974851.shtml)
### 1. Type of Ads & Billings
- 开屏广告
  * 打开APP时第一时间出现的全屏广告
  * 有更强的视觉冲击效果
  * 常见于流量和日活高的应用
    
  展现规则
  * 静态、动态和视频三类广告时间分别为3、4、5秒
  * 支持展示和落地页跳转
    
  计价方式
  * CPM (Cost per thousand / 千人成本): used to identify the cost of every 1,000 impressions on a particular ad
  * 按时间收费, 广告主根据投放时间出价，不受曝光次数影响
    
 
- 信息流广告
  * 信息流广告根据用户兴趣和上下文浏览来推送
  * 相比强曝光的广告形式更原生，定向更精准，
  * 可互动的特性也有利于用户加深品牌印象
    
  展现规则
  (一般是在第3-4位出现，按文字链跳转又分为以下三类。)
  * 落地页广告：跳转H5，常见于培训课程，广告主一般会利用表单来获取用户信息提高转化率。
  * 下载页广告：跳转应用下载页，常见于游戏、教育类APP。
  * 购物页广告：跳转电商平台店铺，常见于服饰、美妆、母婴等品牌
  
  计价方式
  * CPC（点击收费），竞价起步单价0.2元；
  * CPA（实际投放效果计价），按照电话咨询量、APP下载量、表单提交量进行计费。
  
- 挑战赛广告
  * 抖音挑战赛根据广告主需求进行定制推广，类似于话题，但设有专门的话题页面。
  * 常见的挑战赛常吸引用户使用指定贴纸拍摄上传视频，利用创意和互动来进行排名送出奖品，常见于美食类产品。

- 达人带货广告
  * 最初的达人带货限于视频植入或纯软广，抖音小店开通后，达人带货变得更加方便，在主屏上就可以进入小店完成下单转化。
  * 相比前几种广告，带货类广告的转化更加直接。

  展现规则
  * 视频植入或跳转抖音小店
 
  计价方式
   
   
3. sss

[抖音和小红书都在引领流行趋势，二者有何不同？](https://www.niaogebiji.com/article-672863-1.html)
1. 内容形式: 视频VS笔记
2. 内容分发逻辑: 算法VS互动
3. 引领趋势源头：个人VS话题
4. 持续时间：长VS短
5. 覆盖人群：广泛VS垂直
6. 商业模式：电商VS广告
   
* 抖音的电商模式使其在流行趋势的快速变现上具有优势，而小红书的广告模式则更注重长期品牌价值的培养和用户的深度参与。
* 对于追求快速曝光和短期内实现销售转化的品牌，抖音是一个更为合适的选择；而对于那些注重品牌形象长期建设和深度用户关系维护的品牌，则可以考虑在小红书上进行更为深入的内容营销。


## System Design Interview: Design an Ad Click Aggregator 
https://www.hellointerview.com/learn/system-design/answer-keys/ad-click-aggregator

**Ad Click Aggregator** is a system that collects and aggregates data on ad clicks. It is used by advertisers to track the performance of their ads and optimize their campaigns. 

<img width="916" alt="Screenshot 2024-07-18 at 1 04 01 PM" src="https://github.com/user-attachments/assets/a7fd6a29-ac23-4c82-aa90-8d4a7e65b490">


#### Functional Requirements 
1. Users can click on an ad and be redirected to the advertiser's website
2. Advertisers can query ad click metrics over time with a minimum granularity of 1 minute
3. Ad targeting
4. Ad serving
5. Cross device tracking
6. Integration with offline marketing channels

#### Non-Functional Requirements
1. Scalable to support a peak of 10k clicks per second
2. Low latency analytics queries for advertisers (sub-second response time)
3. Fault tolerant and accurate data collection. We should not lose any click data.
4. As realtime as possible. Advertisers should be able to query data as soon as possible after the click.
5. Idempotent click tracking. We should not count the same click multiple times.
(Optional)
6. Fraud or spam detection
7. Demographic and geo profiling of users
8. Conversion tracking


<img width="914" alt="Screenshot 2024-07-18 at 1 01 53 PM" src="https://github.com/user-attachments/assets/1f528fe8-22f7-48d4-840a-2a08e59930f0">


   
