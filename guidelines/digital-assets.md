# Digital Assets

## 檔案選擇

| 情境 | 建議檔案 |
| --- | --- |
| 網站 header、文件或可控制顏色的介面 | `kylewu-mark.svg` |
| 主網站 favicon | `kylewu-favicon.svg` |
| 固定深色底的 app icon 主檔 | `kylewu-app-icon.svg` |
| 不支援 SVG 的小尺寸 favicon | `exports/favicon-32.png` |
| PWA、profile icon 或平台上傳 | `exports/icon-192.png`、`exports/icon-512.png` |
| 只需要姓名的編輯式標題 | `kylewu-wordmark.svg` |
| 同時需要 mark 與姓名 | `kylewu-lockup.svg` |
| 動態或靜態分享圖的背景 | `templates/og-background.svg` 或 `.png` |

## SVG 使用

- 優先使用 SVG，保留向量清晰度。
- 裝飾性 logo 使用空的 `alt` 或 `aria-hidden="true"`。
- Logo 是唯一識別內容時，替代文字使用 `Kyle Wu`，不要寫成 `logo image`。
- 不要從 GitHub Raw hotlink；複製到使用端 repository 並由同一站點提供。
- 變更 fill 顏色時使用核准色或專案規範中的核准組合。

## PNG exports

PNG icon 使用 `Night #121212` 背景、`Cream #f0eadd` mark 與約 18.75% 的圓角。這是沒有自動深淺色切換能力時的預設版本。

不要將 32px 圖檔放大。若平台需要其他尺寸，從 SVG 重新輸出。

## Open Graph

- 固定尺寸：`1200 × 630px`。
- 文字安全區：四周至少 `52px`，主要內容建議由左側 `70px` 開始。
- 左上放 eyebrow 與 mark；中段放頁面標題與副標題；底部放作者與網域。
- 頁面標題與語言應跟目前 URL 一致。
- Kyle Wu 主站可使用 `og-background`；專案網站可以使用自己的底色與內容結構。
- 分享圖右下角或 footer 的識別顏色，應與左上品牌識別使用同一色系。
- 輸出後檢查 1200 × 630、文字沒有裁切，且檔案大小適合網路傳輸。

## 命名與版本

- 使用小寫 kebab-case，例如 `kylewu-mark.svg`。
- 尺寸輸出使用後綴，例如 `icon-512.png`。
- 不在檔名加入 `final`、`new` 或日期；需要發佈歷史時使用 Git tag。
- 使用端若有客製顏色，檔名應加入專案名稱，例如 `kaiyn-favicon.svg`。

## 發佈前檢查

1. SVG 可通過 XML parser。
2. PNG 尺寸與 alpha channel 符合用途。
3. 16px、32px 與 Retina 尺寸下 mark 仍置中且可辨識。
4. 深色與淺色背景上都有足夠對比。
5. OG 圖以英文與繁體中文實際文字各檢查一次。
