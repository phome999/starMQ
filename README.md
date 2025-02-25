# StarMQ1.0

### 开源不意味着可以恶意倒卖！保留版权信息，尊重开源精神！

## 耻辱柱

| 网站名称                   | 链接                                       | 原因                     |
| -------------------------- | ------------------------------------------ | ------------------------ |
| 南轩博客(QQ：82532203)     | https://ns16.cn/215.html                   | 恶意倒卖                 |
| 昔年资源网(QQ：1037967009) | https://www.79ne.cn/1018.html              | 恶意倒卖                 |
| 刀客源码网(QQ：1302357281) | https://www.dkewl.com/code/detail2612.html | 修改版权信息             |
| 刘毅资源网(QQ：71591989)   | https://www.liuyiu.com/113.html            | 恶意倒卖                 |
| 源码之家(QQ：1778458908)   | https://www.pigsns.cn/1655.html            | 修改版权信息             |
| 酷库博客(QQ：8670468)      | https://www.zxki.cn/wzym/5567.html         | 修改版权信息             |
| K1 源码(QQ：3647255)       | https://www.k1ym.com/18526.html            | 恶意倒卖                 |
| 绮梦资源网(QQ：2152443500) | https://www.qmo6.com/19790.html            | 修改版权(提醒后仍不改回) |

## 介绍

- 本系统是为个人用户设计的收款免签约解决方案
- 拒绝高风险的扫码登录方式，采用 APP 监听系统收款通知方案，更安全可靠！
- 基于[ThinkPHP](https://www.thinkphp.cn/)框架开发

## 本项目由[星云数据](https://cloud.staridc.cn)独家赞助！

## 运行环境

- `PHP 8.0` PHP 版本向下兼容至 7.4
- `MySQL 5.7` MySQL 版本向下兼容至 5.6
- `Nginx 1.20.2`

## 预览

![](https://cdn.wgbor.cn/uploads/2023/02/02/167532925963db7eebdb8c9.png)

## 安装教程

1. 下载程序
2. 上传程序至服务器
3. 导入 star.sql 至数据库
4. 修改程序`config/database.php`文件的数据库配置信息（如下图）
   ![](https://cdn.wgbor.cn/uploads/2023/02/02/167532567063db70e6d4724.png)
5. 访问域名即可！

## Tips

- 默认账号密码为`admin` `123456`
- 项目运行目录选择 `public`
- 伪静态设置为`ThinkPHP`

```
location / {
	if (!-e $request_filename){
		rewrite  ^(.*)$  /index.php?s=$1  last;   break;
	}
}
```

- APP 监控软件为根目录的 StarMQ.apk
  [点击下载](./StarMQ.apk)

## 项目推荐

[CloudZA API 一款开源的 API 系统](https://github.com/iCloudZA/CloudZA_API)

## 捐赠

- 如果你觉得程序好用的话，不妨通过捐赠的方式支持我持续更新~
<center style="display:flex;">
<img src="./wx.jpg" width="50%">
<img src="./ali.jpg" width="50%">
</center>

## 捐赠记录

- 鸣谢以下用户对本系统的支持！

| 昵称                       | 联系方式      | 赞助方式 | 金额  |
| -------------------------- | ------------- | -------- | ----- |
| HK-Greatness               | 350**\*\***05 | 微信     | 55.00 |
|                            | 144**\*\***61 | QQ       | 5.00  |
| 绝世                       | 110**\*\***41 | 微信     | 8.88  |
| 知识驿站                   | 267**\*\***57 | 微信     | 6.60  |
| 再飞行                     | 35**\*\***77  | 微信     | 8.88  |
| WEN                        | 18**\*\***25  | QQ       | 5.00  |
| 星际                       | 32**\*\***39  | QQ       | 44.44 |
| 共享节点给你使用小火箭账号 | 144**\*\***61 | 微信     | 5.00  |

## 问题反馈

- 邮箱： `i@kain8.cn`
- QQ 群：`758107405`
- QQ：`1361582519`
