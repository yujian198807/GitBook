## 微信小游戏内嵌游戏导量模块SDK使用说明 ##

###导量模块**gamesharing**
####1. 下载SDK工具包，链接地址[ http://sdkdoc.mrglee.net/gamesharing/gamesharing.zip]( http://sdkdoc.mrglee.net/gamesharing/gamesharing.zip "工具包")
####2. 将SDK工具包解压到开发者所在的项目的 **assets/resources** 目录下。___(注意，不得删除或修改其中的.meta文件)___
####3. 添加工具包中的预制体**GameSharing.prefab**到主界面上
####4. 修改**assets/resources/gamesharing/scripts/GameSharingConfig.ts**内的配置信息。___(注意，微信的AppId和AppSecret需发给相关人员进行后台配置)___
####5. 将需要跳转的小程序的appid添加到game.json___(注意，最多10个)___，如`"navigateToMiniProgramAppIdList": ["wx0393fb39a01f4f4b"]`