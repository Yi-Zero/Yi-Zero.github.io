### 前言：
经过一个多月的调整，本接口重新上线，欢迎各位调用。

#### 接口详细信息以及软件收录表请前往博客文章查看：[主流游戏平台&实用工具安装包下载直链API](https://yizero.top/index.php/2025/01/11/%e4%b8%bb%e6%b5%81%e6%b8%b8%e6%88%8f%e5%b9%b3%e5%8f%b0%e5%ae%9e%e7%94%a8%e5%b7%a5%e5%85%b7%e5%ae%89%e8%a3%85%e5%8c%85%e4%b8%8b%e8%bd%bd%e7%9b%b4%e9%93%beapi/)

### 接口简介：
返回主流游戏平台以及实用工具的安装包下载直链，方便下载，目前已收录24款软件(持续更新)。

本接口只提供安装包下载链接，所有链接均来自网络收集，如有侵权需要删除请联系：sk.yizeroo@gmail.com 

发送邮件后将会在7天内回复您。

欢迎各位在评论区提交自己想要增加的软件名称，我后续会在API中加入。

### 接口地址：
~~~ 
https://api.yizero.top/SoftwareDownloads/API.php
~~~

### 请求参数：
~~~ 
https://api.yizero.top/SoftwareDownloads/API.php
~~~

### 访问方式：
~~~ 
GET
~~~ 

### 返回格式：
~~~ 
JSON
~~~ 

### 返回示例(局部参数)：
~~~
{
    "0": { //JSON排序的ID
        "id": "1", //软件在数据库的ID，此ID固定不会变
        "name": "Steam", //软件名称
        "icon": "", //软件图标
        "introduce": "Steam 是一个提供数千款游戏、社区、硬件和服务的在线平台。您可以在 Steam 上购买、下载、更新、讨论、直播、创作和分享您喜欢的游戏。", //软件简介
        "url": "https://cdn.akamai.steamstatic.com/client/installer/SteamSetup.exe" //软件安装包下载直链
    },
    "1": {
        "id": "2", 
        "name": "Epic",
        "icon": "", 
        "introduce": "下载畅玩各类 PC 平台游戏。. 模组、DLC 和免费游戏等你来享！. 总有一款游戏适合你。", 
        "url": "https://launcher-public-service-prod06.ol.epicgames.com/launcher/api/installer/download/EpicGamesLauncherInstaller.msi"
    }, 
    "Last_updated": "2024年10月1日" //这里是链接最后更新时间，所有链接不定期更新，如有失效链接请及时在评论区反馈。
}

~~~

### 项目状态：
|   类型    |  状态|
| ----------- | ----------- |
| 长期维护      |  ✅       |

