
![Licence](https://img.shields.io/badge/licence-none-green.svg)

# 愿支付（wish-pay）

## 整合支付模块（微信支付，支付宝支付）

### 特性

    1. 不依赖任何 mvc 框架，分层次比较简单
    2. 也不依赖 servlet，作为工具jar使用，可以轻松接入到任何系统里
    3. 支付请求调用支持HTTP和异步、支持http代理
    4. LogBack日志记录
    5. 简单快速完成支付模块的开发
    6. 支持多种支付类型多支付账户扩展（目前已支持微信支付，支付宝支付）
    
### 本项目包含 3 个部分：

     1. wish-pay-core  公共lib,支付核心与规范定义
         1.1 wish-pay-ali  整合支付宝支付
         1.2 wish-pay-wx   整合微信支付
         1.3 wish-pay-common  常用工具包以及公共接口定义
     2. wish-pay-web  一个用springboot的支付demo
   

### 使用
可以参照demo例子中的入口进行使用
** 另外：本项目刚写不久，肯定会有一些bug，如果有志同道合的朋友（ 先加我qq，我拉你进群）可以一起进行修补或者开发其他新功能 **

### 下一版本：
1. 增加对账单功能
2. alipay改成http调用方式
3. 增加几种支付场景的演示

### 联系组织
1. QQ群:564621696
2. 邮箱：fanqinghui100@126.com

