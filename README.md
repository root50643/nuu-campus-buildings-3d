# 國立聯合大學校園建築 3D 模型

本專案收錄國立聯合大學建築物的 3D 模型、可編輯原始檔與實際模型預覽。說明與建築名稱使用繁體中文。

目前已完成並收錄 **29 組近似外觀模型**；以下逐項列出已收錄的館舍及建築群。其餘館舍仍持續整理；本專案不宣稱已涵蓋全校建築。

[兩校區建築研究目錄](docs/CATALOG.zh-TW.md)整理了 **50 筆建物／附屬量體候選**；這不是 50 棟現存獨立建築的斷言，也不是完成率分母。部分歷史館舍、代碼與附屬量體仍待確認。另提供 [JSON 清單](docs/catalog.json)與 [CSV 清單](docs/catalog.csv)。

所有模型都是獨立展示小模型，**並非全校統一比例尺**；均已做數位網格檢查，但尚未實體試印。

## 已完成建築

### 八甲校區 L1｜國鼎圖書館

- [模型檔案與詳細說明](buildings/guoding-library/README.md)
- [150 mm 列印用 STL](buildings/guoding-library/guoding_library_150mm.stl)
- [可編輯 Blender 原始檔](buildings/guoding-library/guoding_library.blend)
- [完整原始檔套件](buildings/guoding-library/guoding_library_150mm_source.zip)

#### 正面透視

![國鼎圖書館 3D 模型正面透視](buildings/guoding-library/front_perspective.png)

#### 正立面

![國鼎圖書館 3D 模型正立面](buildings/guoding-library/front_elevation.png)

#### 背面透視

![國鼎圖書館 3D 模型背面透視](buildings/guoding-library/rear_perspective.png)

以上圖片均為實際模型渲染。模型依公開外觀資訊進行近似重建，並非現場測量、BIM 施工圖或官方精確模型；未經實體試印。尺寸、簡化方式、來源與列印限制請參閱各建築的說明。


### 八甲校區 A1｜理工學院一館

包含 A1a、A1b、A1c 建築群；保留三面主翼、中庭、前端入口量體與分段山牆屋頂。比例按公開外觀估算，未見立面及連廊採簡化處理。 含底座尺寸約 **150 × 148 × 57.1 mm**。

- [建築說明、來源與列印限制](buildings/bajia-a1-science-engineering-1/README.zh-TW.md)
- [STL 模型](buildings/bajia-a1-science-engineering-1/model.stl)・[Blender 場景](buildings/bajia-a1-science-engineering-1/scene.blend)・[網格驗證](buildings/bajia-a1-science-engineering-1/validation.json)

![八甲校區 A1｜理工學院一館實際模型正面](buildings/bajia-a1-science-engineering-1/previews/front.png)

![八甲校區 A1｜理工學院一館實際模型背面](buildings/bajia-a1-science-engineering-1/previews/rear.png)

### 八甲校區 A2｜理工學院二館

保留 U 形中庭、三側量體、斜屋頂、角塔與屋頂太陽能板。未見背面、遮蔽轉角與部分窗帶採近似配置。 含底座尺寸約 **150 × 145 × 58.20 mm**。

- [建築說明、來源與列印限制](buildings/bajia-a2-science-engineering-2/README.md)
- [STL 模型](buildings/bajia-a2-science-engineering-2/model.stl)・[Blender 場景](buildings/bajia-a2-science-engineering-2/scene.blend)・[網格驗證](buildings/bajia-a2-science-engineering-2/validation.json)

![八甲校區 A2｜理工學院二館實際模型正面](buildings/bajia-a2-science-engineering-2/previews/front.png)

![八甲校區 A2｜理工學院二館實際模型背面](buildings/bajia-a2-science-engineering-2/previews/rear.png)

### 二坪山校區 C1｜立德樓（管理學院）

保留八層主要窗列、凸出柱帶、兩層高入口門廊與階梯。背面資料不足，素面後側與推定凹口不應視為已查證的真實立面。底座最長邊為 150 mm。

- [建築說明、來源與列印限制](buildings/erping-c1-lide/README.zh-TW.md)
- [STL 模型](buildings/erping-c1-lide/model.stl)・[Blender 場景](buildings/erping-c1-lide/scene.blend)・[網格驗證](buildings/erping-c1-lide/validation.json)

![二坪山校區 C1｜立德樓（管理學院）實際模型正面](buildings/erping-c1-lide/previews/front.png)

![二坪山校區 C1｜立德樓（管理學院）實際模型背面](buildings/erping-c1-lide/previews/rear.png)

## 檔案組織

每棟建築置於 buildings 下的獨立資料夾，保留自己的繁體中文說明、STL、Blender 檔案、建模程式、驗證結果與圖片。後續只會將完成並檢查過的模型標示為已完成。


### 八甲校區 B1｜電機工程館

含底座尺寸約 **122 × 150 × 90.3 mm**。依公開外觀資料近似重建；未見立面與背面採簡化推定，並非測量或施工模型。獨立展示尺度，尚未實體試印。

- [建築說明、公開來源與列印限制](buildings/bajia-b1-electrical-engineering/README.zh-TW.md)
- [STL 模型](buildings/bajia-b1-electrical-engineering/model.stl)・[Blender 場景](buildings/bajia-b1-electrical-engineering/scene.blend)・[網格驗證](buildings/bajia-b1-electrical-engineering/validation.json)

![電機工程館實際模型正面](buildings/bajia-b1-electrical-engineering/previews/front.png)

![電機工程館實際模型背面近似](buildings/bajia-b1-electrical-engineering/previews/rear.png)


### 八甲校區 B2｜電子工程館

含底座尺寸約 **150 × 50 × 41.5 mm**。依公開外觀資料近似重建；未見立面與背面採簡化推定，並非測量或施工模型。獨立展示尺度，尚未實體試印。

- [建築說明、公開來源與列印限制](buildings/bajia-b2-electronics-engineering/README.md)
- [STL 模型](buildings/bajia-b2-electronics-engineering/model.stl)・[Blender 場景](buildings/bajia-b2-electronics-engineering/scene.blend)・[網格驗證](buildings/bajia-b2-electronics-engineering/validation.json)

![電子工程館實際模型正面](buildings/bajia-b2-electronics-engineering/previews/front.png)

![電子工程館實際模型背面近似](buildings/bajia-b2-electronics-engineering/previews/rear.png)


### 八甲校區 B3｜光電館

含底座尺寸約 **150 × 90 × 64 mm**。依公開外觀資料近似重建；未見立面與背面採簡化推定，並非測量或施工模型。獨立展示尺度，尚未實體試印。

- [建築說明、公開來源與列印限制](buildings/bajia-b3-photonics-engineering/README.zh-TW.md)
- [STL 模型](buildings/bajia-b3-photonics-engineering/model.stl)・[Blender 場景](buildings/bajia-b3-photonics-engineering/scene.blend)・[網格驗證](buildings/bajia-b3-photonics-engineering/validation.json)

![光電館實際模型正面](buildings/bajia-b3-photonics-engineering/previews/front.png)

![光電館實際模型背面近似](buildings/bajia-b3-photonics-engineering/previews/rear.png)


## 新增館舍與建築群

### 八甲校區 B4 資訊工程館

校區：八甲校區。 [原始檔與說明](buildings/bajia-b4-computer-science/)

模型外框尺寸（毫米；X × Y × Z）：150 × 70 × 73.2。資料來源：manifest.json。

![八甲校區 B4 資訊工程館：正面](buildings/bajia-b4-computer-science/previews/front.png)

![八甲校區 B4 資訊工程館：背面](buildings/bajia-b4-computer-science/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 國立聯合大學八甲校區客家研究學院 D1 前棟＋D2 後棟

校區：八甲校區。 [原始檔與說明](buildings/bajia-d1-d2-hakka-complex/)

模型外框尺寸（毫米；X × Y × Z）：150 × 118 × 58。資料來源：validation.json:dimensions_mm。

![國立聯合大學八甲校區客家研究學院 D1 前棟＋D2 後棟：正面](buildings/bajia-d1-d2-hakka-complex/previews/front.png)

![國立聯合大學八甲校區客家研究學院 D1 前棟＋D2 後棟：背面](buildings/bajia-d1-d2-hakka-complex/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 國立聯合大學八甲校區人文與社會學院 E1前棟＋E2中棟＋E3後棟

校區：八甲校區。 [原始檔與說明](buildings/bajia-e1-e2-e3-humanities/)

模型外框尺寸（毫米；X × Y × Z）：150 × 120 × 61。資料來源：validation.json:dimensions_mm。

![國立聯合大學八甲校區人文與社會學院 E1前棟＋E2中棟＋E3後棟：正面](buildings/bajia-e1-e2-e3-humanities/previews/front.png)

![國立聯合大學八甲校區人文與社會學院 E1前棟＋E2中棟＋E3後棟：背面](buildings/bajia-e1-e2-e3-humanities/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 國立聯合大學八甲校區 G1／G2／G3 共同教育館舍組

校區：八甲校區。 [原始檔與說明](buildings/bajia-g1-g2-g3-common-education/)

模型外框尺寸（毫米；X × Y × Z）：150 × 108 × 56。資料來源：validation.json:dimensions_mm。

![國立聯合大學八甲校區 G1／G2／G3 共同教育館舍組：正面](buildings/bajia-g1-g2-g3-common-education/previews/front.png)

![國立聯合大學八甲校區 G1／G2／G3 共同教育館舍組：背面](buildings/bajia-g1-g2-g3-common-education/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### F1 建築一館

校區：二坪山校區。 [原始檔與說明](buildings/erping-f1-architecture-1/)

模型外框尺寸（毫米；X × Y × Z）：150 × 80 × 93.8。資料來源：validation.json:dimensions_mm。

![F1 建築一館：正面](buildings/erping-f1-architecture-1/previews/front.png)

![F1 建築一館：背面](buildings/erping-f1-architecture-1/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### F2 建築二館

校區：二坪山校區。 [原始檔與說明](buildings/erping-f2-architecture-2/)

模型外框尺寸（毫米；X × Y × Z）：150 × 76 × 50.2。資料來源：validation.json:dimensions_mm。

![F2 建築二館：正面](buildings/erping-f2-architecture-2/previews/front.png)

![F2 建築二館：背面](buildings/erping-f2-architecture-2/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### F3 公弢樓

校區：二坪山校區。 [原始檔與說明](buildings/erping-f3-gongtao/)

模型外框尺寸（毫米；X × Y × Z）：150 × 106 × 76.2。資料來源：validation.json:dimensions_mm。

![F3 公弢樓：正面](buildings/erping-f3-gongtao/previews/front.png)

![F3 公弢樓：背面](buildings/erping-f3-gongtao/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 產研創新暨推廣大樓

校區：二坪山校區。 [原始檔與說明](buildings/erping-h1-innovation-outreach/)

模型外框尺寸（毫米；X × Y × Z）：150 × 80 × 121.4。資料來源：manifest.json。

![產研創新暨推廣大樓：正面](buildings/erping-h1-innovation-outreach/previews/front.png)

![產研創新暨推廣大樓：背面](buildings/erping-h1-innovation-outreach/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。


## 宿舍、活動與教學館舍

### 第一宿舍（水雲樓）

校區：二坪山。 [原始檔與說明](buildings/erping-m1-shuiyun-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 108 × 63.1。資料來源：validation.json:dimensions_mm。

![第一宿舍（水雲樓）：正面](buildings/erping-m1-shuiyun-dorm/previews/front.png)

![第一宿舍（水雲樓）：背面](buildings/erping-m1-shuiyun-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 第二宿舍（紅夢樓）

校區：二坪山。 [原始檔與說明](buildings/erping-m2-hongmeng-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 70 × 64.84。資料來源：validation.json:dimensions_mm。

![第二宿舍（紅夢樓）：正面](buildings/erping-m2-hongmeng-dorm/previews/front.png)

![第二宿舍（紅夢樓）：背面](buildings/erping-m2-hongmeng-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 第三宿舍（影山樓）

校區：二坪山。 [原始檔與說明](buildings/erping-m3-yingshan-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 76 × 74.9。資料來源：validation.json:dimensions_mm。

![第三宿舍（影山樓）：正面](buildings/erping-m3-yingshan-dorm/previews/front.png)

![第三宿舍（影山樓）：背面](buildings/erping-m3-yingshan-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 第四宿舍（霽齋樓）

校區：二坪山。 [原始檔與說明](buildings/erping-m4-jizhai-dorm/)

模型外框尺寸（毫米；X × Y × Z）：76 × 150 × 62.14。資料來源：validation.json:dimensions_mm。

![第四宿舍（霽齋樓）：正面](buildings/erping-m4-jizhai-dorm/previews/front.png)

![第四宿舍（霽齋樓）：背面](buildings/erping-m4-jizhai-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 二坪山 M5 第五宿舍（恕先樓）

校區：二坪山校區。 [原始檔與說明](buildings/erping-m5-shuxian-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 94 × 73.4。資料來源：manifest.json。

![二坪山 M5 第五宿舍（恕先樓）：正面](buildings/erping-m5-shuxian-dorm/previews/front.png)

![二坪山 M5 第五宿舍（恕先樓）：背面](buildings/erping-m5-shuxian-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 八甲 M6 第六宿舍

校區：八甲校區。 [原始檔與說明](buildings/bajia-m6-sixth-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 136 × 84。資料來源：manifest.json。

![八甲 M6 第六宿舍：正面](buildings/bajia-m6-sixth-dorm/previews/front.png)

![八甲 M6 第六宿舍：背面](buildings/bajia-m6-sixth-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 二坪山 M7 第七宿舍（雙電樓）

校區：二坪山校區。 [原始檔與說明](buildings/erping-m7-shuangdian-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 122 × 90.2。資料來源：manifest.json。

![二坪山 M7 第七宿舍（雙電樓）：正面](buildings/erping-m7-shuangdian-dorm/previews/front.png)

![二坪山 M7 第七宿舍（雙電樓）：背面](buildings/erping-m7-shuangdian-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 二坪山 M8 第八宿舍（國鼎館）

校區：二坪山校區。 [原始檔與說明](buildings/erping-m8-kuoting-dorm/)

模型外框尺寸（毫米；X × Y × Z）：150 × 108 × 97.99。資料來源：manifest.json。

![二坪山 M8 第八宿舍（國鼎館）：正面](buildings/erping-m8-kuoting-dorm/previews/front.png)

![二坪山 M8 第八宿舍（國鼎館）：背面](buildings/erping-m8-kuoting-dorm/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 八甲 M10 第十宿舍＋M11 第十一宿舍（連通建築群）

校區：八甲校區。 [原始檔與說明](buildings/bajia-m10-m11-dorm-complex/)

模型外框尺寸（毫米；X × Y × Z）：150 × 106 × 65.9。資料來源：manifest.json。

![八甲 M10 第十宿舍＋M11 第十一宿舍（連通建築群）：正面](buildings/bajia-m10-m11-dorm-complex/previews/front.png)

![八甲 M10 第十宿舍＋M11 第十一宿舍（連通建築群）：背面](buildings/bajia-m10-m11-dorm-complex/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 大禮堂、體育館及活動中心

校區：二坪山。 [原始檔與說明](buildings/erping-j1-auditorium-gym-activity-center/)

模型外框尺寸（毫米；X × Y × Z）：150 × 102 × 117。資料來源：manifest.json。

![大禮堂、體育館及活動中心：正面](buildings/erping-j1-auditorium-gym-activity-center/previews/front.png)

![大禮堂、體育館及活動中心：背面](buildings/erping-j1-auditorium-gym-activity-center/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 教學大樓（一）

校區：二坪山。 [原始檔與說明](buildings/erping-k2-teaching-building-1/)

模型外框尺寸（毫米；X × Y × Z）：150 × 64 × 47.7。資料來源：manifest.json。

![教學大樓（一）：正面](buildings/erping-k2-teaching-building-1/previews/front.png)

![教學大樓（一）：背面](buildings/erping-k2-teaching-building-1/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 教學大樓（二）

校區：二坪山。 [原始檔與說明](buildings/erping-k3-teaching-building-2/)

模型外框尺寸（毫米；X × Y × Z）：150 × 64 × 59.99。資料來源：manifest.json。

![教學大樓（二）：正面](buildings/erping-k3-teaching-building-2/previews/front.png)

![教學大樓（二）：背面](buildings/erping-k3-teaching-building-2/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

### 資訊大樓與國際會議中心低層連通部分

校區：八甲。 [原始檔與說明](buildings/bajia-i1-r1-information-conference/)

模型外框尺寸（毫米；X × Y × Z）：150 × 110 × 103.9。資料來源：manifest.json。

![資訊大樓與國際會議中心低層連通部分：正面](buildings/bajia-i1-r1-information-conference/previews/front.png)

![資訊大樓與國際會議中心低層連通部分：背面](buildings/bajia-i1-r1-information-conference/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。

範圍提醒：本件合含 I1 資訊大樓及 R1 國際會議中心低層連通部分，不另重複計為兩件，且不含 L1 圖書館。

### 藝文教學中心（藝術中心）

校區：八甲。 [原始檔與說明](buildings/bajia-q1-arts-teaching-center/)

模型外框尺寸（毫米；X × Y × Z）：150 × 100 × 61。資料來源：manifest.json。

![藝文教學中心（藝術中心）：正面](buildings/bajia-q1-arts-teaching-center/previews/front.png)

![藝文教學中心（藝術中心）：背面](buildings/bajia-q1-arts-teaching-center/previews/rear.png)

外觀與背側細節含推估及簡化；非實測復刻，未經實體試印。
