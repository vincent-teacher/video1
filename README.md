# 🎬 互動式教學影片館（video1）

把課本 PDF 教材轉換成 **9:16 直式（1080×1920）、5 分鐘自動播放** 的互動式視覺化教學網頁。
每支影片都是 **單一 HTML 檔＋內嵌 SVG**，具有投影片轉場、動畫元素、旁白配音與同步字幕，像看影片一樣上課。

🔗 **首頁**：<https://vincent-teacher.github.io/video1/>（需在儲存庫 Settings → Pages 啟用 GitHub Pages，來源選 `main` 分支根目錄）

## 📚 影片清單

| 學科 | 主題 | 資料夾 | 投影片數 | 段落 |
|---|---|---|---|---|
| 國文 | [出師表](chinese-chu-shi-biao/index.html) | `chinese-chu-shi-biao/` | 14 | 引言、作者與背景、文章結構、三大建議、自述與期許、名句與總結 |
| 英文 | [The Lady or the Tiger?](english-lady-or-tiger/index.html) | `english-lady-or-tiger/` | 15 | 引言、故事背景、人物與衝突、高潮與結局、語言重點、總結 |
| 數學 | [線性規劃](math-linear-programming/index.html) | `math-linear-programming/` | 15 | 引言、平行直線系、二元一次不等式、線性規劃、應用題、總結 |
| 物理 | [摩擦力：靜摩擦與動摩擦](physics-friction/index.html) | `physics-friction/` | 14 | 引言、靜摩擦力、斜面分析、範例、動摩擦力、總結 |
| 化學 | [化學式與百分組成](chemistry-formula/index.html) | `chemistry-formula/` | 16 | 引言、實驗式、分子式、結構式、示性式、總結 |
| 地理 | [氣候系統：氣候要素](geography-climate/index.html) | `geography-climate/` | 16 | 引言、氣溫、氣壓與風、降水特性、降水類型、應用與總結 |
| 公民 | [所有權的物權特性](civics-ownership/index.html) | `civics-ownership/` | 14 | 引言、所有權是什麼、四大特性、所有權的保障、限制與調和、總結 |

## ✨ 每支影片的特色

- **300 秒自動播放**：依教材切成數個段落，每頁依旁白長度分配時間，總長固定 5 分鐘。
- **視覺化設計**：每張投影片都有內嵌 SVG 圖解（示意圖、圖表、座標圖、時間軸、受力圖…）。
- **動畫與轉場**：元素依旁白節奏逐一出現（淡入、彈出、描線、長條成長、脈動…），換頁有淡入、滑動、縮放、翻轉、擦除、圓形展開等轉場。
- **旁白配音**：使用瀏覽器內建 Web Speech API，預設語音、中等語速（rate 1.0）；英文句子自動改用英文語音。
- **逐字稿字幕**：旁白依語氣切段，每段不超過一個畫面可容納的字數，與語音同步顯示。
- **播放控制**：播放／暫停、上一頁／下一頁、進度條跳轉、旁白開關；鍵盤 `Space`、`←`、`→`、`M`。

## 🗂 內容介紹

### 國文｜出師表

諸葛亮北伐前上呈後主的奏章：從三國情勢、作者生平到文章結構，解析開張聖聽、賞罰分明、親賢遠小人三大建議與名句。

- 線上觀看：<https://vincent-teacher.github.io/video1/chinese-chu-shi-biao/>
- 關鍵詞：出師表、諸葛亮、三國鼎立、開張聖聽、賞罰分明、親賢臣遠小人、三顧茅廬、北伐

### 英文｜The Lady or the Tiger?

從競技場的兩扇門出發，認識殘酷國王、公主與青年的故事，理解公主的兩難與開放式結局，並學習 insist that 與 as…as 句型和關鍵單字。

- 線上觀看：<https://vincent-teacher.github.io/video1/english-lady-or-tiger/>
- 關鍵詞：The Lady or the Tiger、開放式結局、故事結局類型、人物關係、dilemma、insist that、as…as 讓步、單字

### 數學｜線性規劃

從平行直線系與二元一次不等式的圖形出發，認識可行解區域、目標函數與最佳解，學會用平行線法與頂點法解線性規劃應用題。

- 線上觀看：<https://vincent-teacher.github.io/video1/math-linear-programming/>
- 關鍵詞：線性規劃、平行直線系、二元一次不等式、半平面、可行解區域、目標函數、最佳解、平行線法、頂點法

### 物理｜摩擦力：靜摩擦與動摩擦

從推不動的箱子出發，認識靜摩擦力、最大靜摩擦力與動摩擦力，分析斜面受力、用 tanθ 測靜摩擦係數，並以 f–F 關係圖與疊箱範例統整概念。

- 線上觀看：<https://vincent-teacher.github.io/video1/physics-friction/>
- 關鍵詞：靜摩擦力、最大靜摩擦力、動摩擦力、摩擦係數、正向力、斜面、f–F 關係圖

### 化學｜化學式與百分組成

從醋酸出發認識實驗式、分子式、結構式與示性式；學會由質量百分組成與燃燒分析求實驗式，再以分子量推得分子式，並以三聚氰胺素養題練習。

- 線上觀看：<https://vincent-teacher.github.io/video1/chemistry-formula/>
- 關鍵詞：實驗式、分子式、結構式、示性式、百分組成、燃燒分析、同分異構物、官能基

### 地理｜氣候系統：氣候要素

認識氣候三大要素：緯度、高度、海陸與洋流如何影響氣溫，氣壓與風、氣旋反氣旋，以及降水量、強度、季節、變率與四種降水類型。

- 線上觀看：<https://vincent-teacher.github.io/video1/geography-climate/>
- 關鍵詞：氣溫、氣壓、風、氣旋、反氣旋、降水量變率、地形雨、對流雨、鋒面雨、黑潮

### 公民｜所有權的物權特性

從物權與債權的差異出發，認識所有權的使用、收益、處分與排除干涉權能，四大特性（直接支配、保護絕對、排他、優先），民法第767條保障與所有權限制。

- 線上觀看：<https://vincent-teacher.github.io/video1/civics-ownership/>
- 關鍵詞：所有權、物權、債權、直接支配性、保護絕對性、排他性、優先性、民法第767條、物權法定主義、不動產登記

## 🛠 技術說明

```
video1/
├── index.html            # 首頁（影片目錄）
├── README.md
└── <資料夾>/
    ├── index.html        # 單一 HTML 教學影片（內嵌 SVG、CSS、JS）
    └── meta.json         # 影片資訊（首頁與 README 由此產生）
```

- 舞台固定 1080×1920，依視窗大小等比縮放，手機直向或投影全螢幕皆可。
- 播放引擎以時間軸驅動投影片、動畫與字幕；若語音尚未唸完，時間軸會短暫等待以保持音字同步。
- 瀏覽器規定播放語音前需使用者互動，因此開啟後請先點擊「▶」開始。
- 語音品質取決於裝置內建語音（Chrome／Edge／Safari 皆支援；建議安裝中文語音）。

## 📄 教材來源

教材內容取自授課教師提供之 PDF 講義，網頁僅供教學使用。
