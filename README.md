# garden-dianzan
garden-dianzan

安卓手机微信的UA设置
Mozilla/5.0 (Linux; Android 9; Mi Note 3 Build/PKQ1.181007.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/77.0.3865.120 MQQBrowser/6.2 TBS/045331 Mobile Safari/537.36 MMWEBID/9186 MicroMessenger/7.0.19.1760(0x27001339) Process/tools WeChat/arm64 NetType/WIFI Language/en ABI/arm64
手机微信里的链接通过手机微信可以打开，但是发到电脑上打开时提示“请在微信客户端打开链接”，在chrome打开开发者模式，再ctrl shift p 打开运行命令框，搜索 network conditions（网络调节） 并打开。找到下面的 User Agent，设置上面的UA可以在电脑端打开微信中的链接。

GET http://180829.fxcm1199.cn/index.php?g=Wap&m=Vote&a=poster&id=2560&zid=135&token=Eioa5C5oj3S32qhH&_v=1601275225474 HTTP/1.1
Host: 180829.fxcm1199.cn
Connection: keep-alive
Cache-Control: max-age=0
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Linux; Android 9; Mi Note 3 Build/PKQ1.181007.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/77.0.3865.120 MQQBrowser/6.2 TBS/045331 Mobile Safari/537.36 MMWEBID/9186 MicroMessenger/7.0.19.1760(0x27001339) Process/tools WeChat/arm64 NetType/WIFI Language/en ABI/arm64
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3
X-Requested-With: com.tencent.mm
Accept-Encoding: gzip, deflate
Accept-Language: en-US,en;q=0.9
Cookie: __cfduid=ddd650d6d81e57bf7a1ca1e3de09a97b21601275277; PHPSESSID=ucvaosq7ejieuac0bthp93va63; UM_distinctid=174d429603d55-071a7df2db36c6-2b21451c-43113-174d429603e9a
