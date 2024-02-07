# HTML How
推介使用[replit.com](https://replit.com/)、[NetLify](https://www.netlify.com/)或[Github page](https://pages.github.com/)所提供的網頁托管\
Import`https://github.com/JerryIs-strong/personal-webpage.git`from GitHub
預覽: [NetLify](https://jerrypro.netlify.app/)
## 配置項
以下所用配置項均可以透過`setting.json`文件配置，如果你不是開發者，請不要移動或刪除除`setting.json`配置文件以外的文件，以免發生錯誤
### Basic Environment 基本環境
```Json
"basic environment": {
    "website name": "My SPACE", //網站標題(瀏覽器)
    "website description": "海内存知己 天涯若比鄰", //内容描述
    "holder name": "SPACE", //作者名稱
    "holder icon":{
        "method": "local", //作者頭像：1.local | 2.gravatar(自動獲取)
        "local":{
            "url": "/icon.png" //填寫絕對路徑 e.g: sub-background.png
        },
        "gravatar": {
            "email": "tou6ocjzq@mozmail.com" //作者gravatar電郵
        }
    },
    "background":{
        "url": "background.png" //1.Local: 填寫絕對路徑 e.g: background.png | 2.外部鏈接: 添加https://標頭 e.g: https://jerrypro.xyz/background.png
    }
}
```
### Link 鏈接按鈕
```Json
"Link": {
    "link-1": { //鏈接1
        "enabled": true, //enable: 開啓 | false: 關閉
        "icon": "fa-brands fa-facebook", //fontawesome取得icon的名稱 e.g:fa-brands fa-facebook
        "url": "https://facebook.com", //鏈接目標
        "target": "blank" //_blank | _self | _parent | _top
    },
    "link-2": { //鏈接2
        "enabled": true, //enable: 開啓 | false: 關閉
        "icon": "fa fa-youtube", //fontawesome取得icon的名稱 e.g:fa-brands fa-facebook
        "url": "https://youtube.com", //鏈接目標
        "target": "blank" //_blank | _self | _parent | _top
    },
    "link-3": { //鏈接3
        "enabled": true, //enable: 開啓 | false: 關閉
        "icon": "fa fa-link", //fontawesome取得icon的名稱 e.g:fa-brands fa-facebook
        "url": "https://google.com", //鏈接目標
        "target": "blank" //_blank | _self | _parent | _top
    },
    "link-4": { //鏈接4
        "enabled": true, //enable: 開啓 | false: 關閉
        "icon": "fa fa-instagram", //fontawesome取得icon的名稱 e.g:fa-brands fa-facebook
        "url": "https://instagram.com", //鏈接目標
        "target": "blank" //_blank | _self | _parent | _top
    },
    "link-5": { //鏈接5
        "enabled": true, //enable: 開啓 | false: 關閉
        "icon": "fa  fa-telegram", //fontawesome取得icon的名稱 e.g:fa-brands fa-facebook
        "url": "https://web.telegram.org/", //鏈接目標
        "target": "blank" //_blank | _self | _parent | _top
    }
}
```