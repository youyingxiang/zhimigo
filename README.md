## 攻略生活项目计划书
### 项目架构
 - linux系统+docker+laravel6.0+php7.3
 - 总后台+代理商后台+商户后台+api接口 
### 开发流程
  - 数据库设计（三天时间）
  
  - 商户后台管理系统开发（4天）
    - 商品管理
      - 本地商品
      - 第三方商品(淘宝客 拼多多)
    - 商品分类管理
    - 商户广告位管理
    - 内容管理
    - 财务管理
        - 订单管理（当前商户旗下用户购买商品订单）
           - 本地订单
           - 第三方订单(淘宝客 拼多多)  
    - 分销设置           
    - 会员管理（通过该商户注册的会员）
        
   - 代理商后台管理系统开发（3天）
      - 商户管理
      - 订单列表 （当前代理商旗下商户的用户）
      - 返佣账单 （我理解的当前商户下有成交订单 给代理商的提成）
      - 提现记录
      - 商户返佣设置
      
   - 总后台管理系统开发（3天）
      - 代理商管理
      - 商户列表
      - 活动管理
      - 代理商返佣金设置（代理商旗下商户成交订单返回平台的佣金）
      - 淘宝客订单  
        
  - api接口开发（16天 熟悉淘宝客接口 仔细看了下淘宝客接口有很多坑，比如获取买家所有订单这种）
    - 申请成为代理商
    - 申请成为商户
    - 会员注册
        - 手机短信注册
        - 手机短信登陆
        - 是否微信授权 支付宝授权登陆 ？
    - 商品列表
        - 本地商品
        - 淘宝客第三方商品
    - 商品分类
        - 本地商品
        - 淘宝客第三方商品分类
    - 商品物料查询
        - 淘宝客第三方商品物料
        - 本地第三方商品物料
    - 会员订单查询
        - 本地订单
        - 第三方订单
    - 商品详情信息
        - 本地商品详情信息
        - 淘宝客第三方商品详情信息
    - 广告位-banner图接口
        - 本地商品广告位-banner图
        - 第三方商品广告位-banner图
    - 我的粉丝
        - 通过会员拉过来的会员
    - 会员余额
    - 首页活动
        - 淘宝客第三方活动
        - 本地活动
    - 会员订单
        - 淘宝客第三方订单
        - 本地订单  
   - 说明
        - 以上需求是根据竞品初步分析需求，项目一段定下来开始开发。这边就不会再改需求
        - 开始开发前请提供微信公众号,并且是已开通微信支付的
        - 开始开发前请提供淘宝客账户，如果没有申请为开发者需申请
        - 麻烦提供下粉象生活的账户和密码，我体验下在确认下需求。我这边无法注册需要邀请码
   - 开发费用
     - 总费用5万(普通商城完全开发1万,sass开发2万,本地和淘宝客等api接口2万)
     - 首付款1.5万
     - 第一期交付（完成代理商后台商户后台总后台 14天）
     - 第二期开始付款（2万) 
     - 第三期交付(api接口的开发 16天)
     - 项目上线并部署测试环境（1.5万）
   - 项目维护
     - 以上后端现有业务出现问题，一年免费维护。新功能另算
     
     
                      
           
        
        
        
         

