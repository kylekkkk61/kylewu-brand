# Identity

## 名稱

- 主要公開名稱：`Kyle Wu`
- 羅馬拼音姓名：`Ping-Ju Wu`
- 中文姓名：`吳秉儒`
- 中文內容首次提及可使用：`Kyle Wu（吳秉儒）`

不要在同一個標題或導覽中同時堆疊三種姓名。`Ping-Ju Wu` 適合履歷、正式文件或需要與法定姓名對應的情境。

## 定位

跨平台的核心定位為：

> FinTech Builder / Product Strategy / Market Analysis

英文長版：

> Kyle Wu is a Taiwan-based FinTech builder and incoming MSc Financial Technology student at Warwick Business School, working across product strategy, market analysis, digital finance, and AI-native software execution.

繁體中文版：

> Kyle Wu（吳秉儒）來自台灣，是即將就讀華威商學院金融科技碩士的 FinTech Builder，專注於產品策略、市場分析、數位金融與 AI 原生軟體開發。

專案頁可以強調 trading infrastructure、execution quality 或 market microstructure，但不應把這些專案領域取代為整體個人定位。

## Logo 系統

### Master mark

`assets/logo/kylewu-mark.svg` 是幾何主檔。它使用透明背景與深色 ink，適合文件、淺色頁面及後續製作。

### Favicon

`assets/logo/kylewu-favicon.svg` 會依使用者的系統色彩模式切換深淺色。小尺寸顯示包含 18 單位的視覺補強 stroke，這是 favicon 的例外處理，不應回寫到 master mark。

### Wordmark 與 lockup

`kylewu-wordmark.svg` 與 `kylewu-lockup.svg` 使用 Newsreader 600，文字已轉為向量 outline，因此不依賴接收端字型。若要修改姓名文字，應回到 Newsreader 600 重新製作，不要直接拉伸既有路徑。

## 留白與尺寸

- Mark 四周至少保留 mark 可見寬度的 `1/4`。
- Lockup 中不要改變 mark 與姓名的相對比例。
- 一般介面中的 mark 不小於 `20px`；瀏覽器 favicon 是例外。
- 不要旋轉、傾斜、拉伸、加陰影或加入外框。

## 顏色

### Kyle Wu 核心色

| Token | Hex | 用途 |
| --- | --- | --- |
| Ink | `#2c2a29` | 淺色背景上的文字與 mark |
| Paper | `#fbfaf7` | 主站淺色背景 |
| Night | `#121212` | 主站深色背景 |
| Cream | `#f0eadd` | 深色背景上的 mark 與主要文字 |
| Sage | `#9fb396` | 深色模式的輔助重點 |
| Forest | `#4d6146` | 淺色模式的輔助重點 |
| Plum | `#c2a3bc` | 深色模式的第二輔助色 |
| Aubergine | `#61465b` | 淺色模式的第二輔助色 |
| Gold | `#c4a56c` | OG eyebrow 與低比例品牌細節 |

Gold、Sage 與 Plum 都是輔助色，不要同時以高飽和度或大面積競爭。

## 字體

- Heading / editorial name treatment：Newsreader
- Interface / body：Geist
- Data / code / labels：Geist Mono
- 繁體中文 OG 或無法使用 Geist 的中文情境：Noto Sans TC

使用端應自行載入字型；本 repository 不散佈字型檔。
