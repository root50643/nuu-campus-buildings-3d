# 國立聯合大學校園建築 3D 模型

本專案收錄國立聯合大學建築物的 3D 模型、可編輯原始檔與實際模型預覽。說明與建築名稱使用繁體中文。

目前已完成並收錄 **7 組近似外觀模型**，涵蓋國鼎圖書館、理工一館、理工二館、立德樓，以及以下新增的電機、電子、光電館舍。其餘館舍仍持續整理；本專案不宣稱已涵蓋全校建築。

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
