### 接口简介：
返回主流游戏平台安装包的下载直链，方便下载，目前已收录24款软件。

> [!WARNING]
> 此接口于2024年11月3日公开测试，由于服务器性能问题，切勿大量调用！
>如接口出现问题或有新的软件想添加请留下评论.

### 接口地址：
~~~ 
https://api.u299259.nyat.app:35641/SoftwareDownloads/API.php 
~~~

### 请求参数：
~~~ 
https://api.u299259.nyat.app:35641/SoftwareDownloads/API.php 
~~~

### 访问方式：
~~~ 
GET
~~~ 

### 返回格式：
~~~ 
JSON
~~~ 

### 返回示例(已省略大部分参数)：
~~~
{
    "0": {
        "id": "1",
        "name": "Steam",
        "icon": "",
        "introduce": "Steam 是一个提供数千款游戏、社区、硬件和服务的在线平台。您可以在 Steam 上购买、下载、更新、讨论、直播、创作和分享您喜欢的游戏。",
        "url": "https://cdn.akamai.steamstatic.com/client/installer/SteamSetup.exe"
    },
    "1": {
        "id": "2",
        "name": "Epic",
        "icon": "",
        "introduce": "下载畅玩各类 PC 平台游戏。. 模组、DLC 和免费游戏等你来享！. 总有一款游戏适合你。",
        "url": "https://launcher-public-service-prod06.ol.epicgames.com/launcher/api/installer/download/EpicGamesLauncherInstaller.msi"
    },
}

~~~

### 其他信息：
|       |  |
| ----------- | ----------- |
| 长期维护      | ✅       |
