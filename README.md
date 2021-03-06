# 3D-Printer
3D Printer 使用記錄 (Ender3 Pro 就是 Ender3s)

以下為預計要寫的內容，先寫下標題，簡單記錄一下，晚點會把每一項逐步補上

## 組裝
主要是看影片，因為一開始我沒注意到SD卡中有進一步的組裝說明，以為只有一張快整組裝說明書…

- [影片1](https://www.youtube.com/watch?v=2Iy3fc05v_w) -->因為是中文的，我反覆看了很多次
- [影片2](https://www.youtube.com/watch?v=6EdZeodW5qo)
- [影片3](https://www.youtube.com/watch?v=a8Z-9ncYsps&t=92s) : 組好到列印
- [影片4](https://www.youtube.com/watch?v=NceBBAKDLEY) : 一個女生的教學，從組到[調水平，有附gcode](https://www.thingiverse.com/thing:2874536)
- [影片5](https://www.youtube.com/watch?v=_EfWVUJjBdA) : 教調水平，有[調校用的g-code](https://www.thingiverse.com/thing:3235018)

### 用g-code調水平我還沒試過，目前都是讓它回原點後，再手動移動進行調整


## 使用的軟體

### cura15.04.6，是一開始Ender3S的資料中就有附的軟體
  
  - [說明文件](01_使用的軟體/Reference data/Ender-3 Pro Reference data.pdf)中也有建議參數
  - [原廠的參數檔](https://github.com/maloyang/3D-Printer/blob/master/01_%E4%BD%BF%E7%94%A8%E7%9A%84%E8%BB%9F%E9%AB%94/Reference%20data/Ender-3%20Pro.ini)

### cura3.0.2 (應該說是Ultimaker Cura), 其實我不太清楚這和上一個有什麼不同，但朋友一開始是教我用cura15.04.6這個版本的，所以一直沒用過這一個，晚點有用到再補上經驗


## 初始測試

### 印點有關節的作品
- [有關節的骨頭魚-Fish Fossilz](https://www.thingiverse.com/thing:1276095)，是一開始測試基本功能的好圖，如果有問題，關節被連在一起就動不了了…
- [有關節的骨頭魚2](https://www.thingiverse.com/thing:2788255)
- [有關節的暴龍](https://www.thingiverse.com/thing:2738211)，這一個很可愛，因為本來的比較大，我把高度調整為8mm (長寬高都x0.615)，時間也從2:15減為54分，印出來還蠻成功的，只有尾巴最後的節有點轉不會(2019-01-13)
- [蛇](https://www.thingiverse.com/thing:1709106)：一次印了二隻，這個關節好能轉，小孩很愛玩!

### 夾子系列：

- [利用塑料彈力的魚夾子](https://www.thingiverse.com/thing:1734347)，算蠻有趣的，印好後小孩子一直夾在衣服下，不肯拿下來
印了上面這個忽然發現作者還有一系列的作品可以印來玩!
- [蟲子夾-Bugz](https://www.thingiverse.com/thing:1904654)：因為蟲子夾很小，所以一次印二個，也不到50分鐘就印完了
- [啄木鳥-WOODPECKERZ](https://www.thingiverse.com/thing:1155168)：細節蠻好看的，但因為大了一點，所以要印到2個小時
- [鱷魚夾-Crocz](https://www.thingiverse.com/thing:941177)：感覺還不錯看，長型不大，1個多小時可以印完
- [鯊魚夾-Sharkz](https://www.thingiverse.com/thing:910216)：印出來最沒有細節瑕疵的作品，1:20可以印完

- [老鷹夾-Eaglez](https://www.thingiverse.com/thing:963892)：還沒印，先收著


----
### 2019/01/13 印完以上的感覺
- 不設底面Raft，容易一開始就失敗 --> 也許是我水平調的不夠好
- Ender3 Pro的列印平面真的很好用，不用雙面膠、口紅膠也能印的很好
- 在印時會有微微的「牽絲」，目前設定中已有回抽，不知道是怎麼回事 --> [有文章說明，但是用尼龍絲做實驗](https://z3dfilament.blogspot.com/2018/05/StringingTesting.html)

### 可以印來給Ender3S用的零件：
- [線的引導器](https://www.thingiverse.com/thing:2917932)：已印來用，印出來要裝時有點不好裝，所以我剪了部份固定部才裝上去。
- [抽屜: 放小零件用](https://www.thingiverse.com/thing:2989218): 這一組我印了超過24小時，但尺寸不合，還要縮小一下，有需要的人要注意，印之前量一下你的實際空間是不是和他一樣。
- [Cable的蛇管](https://www.thingiverse.com/thing:2920060): 我預計會印來使用

 

## 好作品記錄


## 暫時有興趣的作品…待核

- 自動餵魚器
  - [餵魚器1](https://www.thingiverse.com/thing:1639286)
  - [餵魚器1](https://www.thingiverse.com/thing:2539750)

- [放SD卡的魚](https://www.thingiverse.com/thing:1737367)

- [Hungry Robot](https://www.thingiverse.com/thing:2824451)
- [紙的Hungry Robot，有意思!](https://www.thingiverse.com/thing:2984461)
- 車子：
  - https://www.thingiverse.com/thing:2662828
  
## 3D繪圖

### [TinkerCad](https://www.tinkercad.com/): online cad，適合國中小學生以上使用

- 線上學習(Starter)：
  - [1]放一個方塊，[2]用mouse去view(放大縮小、平移、轉動)，[3]移動方塊，[4]轉動方塊，[5]變動方塊尺寸
  - [6]Group來結合、挖洞，[7]對齊物件
- 線上學習(實作)
  - [1]眼鏡
  - [2]棋子: 練習rectange, cone, sphere形狀，group, workspace, align(用了這一個才知道為何為用對的太準，因為front, side都對到中心，就等於軸心為同一個了)
  - [3]尺：說實在的，這樣的畫法，我真的不是很確定是否畫出來的尺寸是對了…對使用過傳統CAD的人真的不是太好適應…
  
- 要畫的
  - 平面圖-->擠出 -->好像沒這樣的操作方式
  - 畫一個小車底座：有ESP安裝孔、馬達安裝孔、電池固定孔
  - 畫輪子，有servo的固定介面
  - 紅外線固定座
  - 超音波固定座
  - 音樂盒 --> Nano、Buzzer固定介面，接耳機的介面
  - [Arduino車的外殼、輪子](https://www.youtube.com/watch?v=Lz9jQQ5H318)
  
