# HookBasedCrawler

某视频号爬虫

使用技术：Hook + NanoHTTPD + NPS

测试地址：wx.eatan96.cn

请求方式：HTTP / POST

| 参数名    | 必选 | 类型   | 说明                            |
| --------- | ---- | ------ | ------------------------------- |
| user_name | 是   | String | 作者签名                        |
| type      | 是   | String | 请求标识：all：全量、last：增量 |

请求示例：http://wx.eatan96.cn?user_name=v2_060000231003b20faec8c6e18e1dc5d3c90dea35b077c8b2db313047271f29519a11abfb848c@finder&type=last

------

**本地址仅作为研究学习使用，请勿用于非法用途。**

**不可违法，不可商用，服务器和爬虫程序对收到的请求均做了限制。**

**服务器对于同一个公网IP的请求频率限制为10秒1次。少于10秒则返回503。**

**爬虫程序并发数为1，同一时间段仅处理一个请求。**

