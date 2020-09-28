# garden-dianzan
garden-dianzan

安卓手机微信的UA设置
Mozilla/5.0 (Linux; Android 9; Mi Note 3 Build/PKQ1.181007.001; wv) AppleWebKit/537.36 (KHTML, like Gecko) Version/4.0 Chrome/77.0.3865.120 MQQBrowser/6.2 TBS/045331 Mobile Safari/537.36 MMWEBID/9186 MicroMessenger/7.0.19.1760(0x27001339) Process/tools WeChat/arm64 NetType/WIFI Language/en ABI/arm64
手机微信里的链接通过手机微信可以打开，但是发到电脑上打开时提示“请在微信客户端打开链接”，在chrome打开开发者模式，再ctrl shift p 打开运行命令框，搜索 network conditions（网络调节） 并打开。找到下面的 User Agent，设置上面的UA可以在电脑端打开微信中的链接。
