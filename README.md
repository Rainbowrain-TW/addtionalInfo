## Rain's Addtional Experience

#### 資策會時期的 iOS 作品
![Imgur](https://i.imgur.com/J1Oag2B.jpg)

-----

### 在宗偉科技的第一個專案

#### 醫院診間的叫號系統
- **simpy mode**

![Imgur](https://i.imgur.com/5gqE2JL.jpg)

- **full mode**

![Imgur](https://i.imgur.com/veaz5QG.jpg)

-----

#### 儀器資料收集系統
- **主畫面**
![Imgur](https://i.imgur.com/KQHqLPo.jpg)

- **參數設定功能**
![Imgur](https://i.imgur.com/sK1mzGy.jpg)

-----

#### 儀器資料確認介面(vanilla JS)
- **儀器選擇畫面**
![Imgur](https://i.imgur.com/cQomPKI.png)

- **數據結算畫面** -
![Imgur](https://i.imgur.com/hf8zij4.png)

-----

#### SBC 廣告機 Electron.js

[trello link](https://trello.com/b/RrROGoon/%E5%82%99%E4%BB%BD-sbc%E5%BB%A3%E5%91%8A%E6%A9%9F)

主要功能：用 Electron.js 搭建一個顯示網頁的應用程式骨幹跑在 Linux 系統（Raspberry Pie & Nvidia Jetson Nano）

功能列表：
- 解析度調整
- 顯示方向調整（Linux GUI & Electron App）
- App 可用性監控（透過 Azure insight & Local log 記錄, Websocket Heartbeat 監控, Slack Webhook 通知）
- Device Status Dashboard（溫度、CPU&MEM 用量、開機時長）
- 自動啟動&重啟 App
- 遠端啟動 App
- 透過序列控制電視機設定

#### OAuth2 API & SSO

參考 RFC6749 實作 OAuth2 Provider

-----

#### Google translate extension modify

如果你曾經遇到過要在頁面選取翻譯時明明是英文卻顯示是中文，打開語言列表那一張串看不出邏輯的語言排列順序害你想選個英文都找到心累，更慘的是有這種狀況的網頁幾乎選取哪個英文要翻譯都會有一樣的狀況。

那這個修改版可以幫你一點忙。經過修改之後目前把 11 國我覺得可能比較常用的語言移到選單最上方。

按順序排序為 1. 英文 2. 日文 3. 韓文 4. 泰文 5. 德文 6. 法文 7. 俄文 8. 義大利文 9. 西班牙文 10. 中文 11. 自動偵測

不在上列的語言會先經過字母排序（由 a 到 z ）接在後面。

優先順位名單可以自己調整檔案中的某行簡單的變更順序及新增或移除。

[Trello Card Link](https://trello.com/c/XM6tO0mZ)

-----

#### React Practice

[ToDo List](https://codepen.io/rainbowrain/pen/KLoZVo?editors=0110)

[JobFinder](http://rainbowrain.tw/react/demo/)
