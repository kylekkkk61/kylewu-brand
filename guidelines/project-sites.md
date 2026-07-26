# Project Sites

## 關係模型

`kylewu.me` 是個人品牌與完整 case study 的主要入口。專案網站則負責 demo、工程文件、研究證據或產品操作脈絡。

專案網站不需要看起來像主網站的子頁面。共同識別應集中在少數穩定元素：

- Kyle Wu mark 或 favicon
- 清楚的作者資訊
- 回到 `https://kylewu.me` 或對應 case study 的連結
- 一致且準確的專案名稱與描述
- 不互相矛盾的 metadata、README 與可見內容

## 必要元素

每個公開專案網站至少應包含：

1. 一個明確的專案名稱與一句用途說明。
2. 作者或維護者識別：`Kyle Wu`。
3. 返回主網站對應 case study 的文字連結。
4. Repository 連結與專案目前狀態。
5. 專案 favicon、Open Graph metadata、canonical URL、robots.txt 與 sitemap.xml。
6. 若內容含示意數字、模擬或非實盤結果，在數字附近直接說明限制。

## Kaiyn Trading Bot

### 定位

工程與產品專案，重點是 confirmation-first workflow、風險控制、狀態管理與操作文件。不要將網站寫成績效行銷頁，也不要保證完全消除 duplicated orders。

### 核准視覺

| Role | Hex |
| --- | --- |
| Background | `#07111f` |
| Accent / mark | `#38c7f4` |

可以使用 Kyle Wu mark 的專案色版本，但不得改變 mark 幾何。主視覺保持工程系統感，不需要套用主站的 Morandi 背景。

## Prediction Market Execution Lab

### 定位

正式英文名稱保留 `Prediction Market Execution Lab`。在繁體中文敘述中稱為「公開研究專案」，不要逐字翻成「預測市場執行實驗室」。

內容以方法、限制、可執行性與公開樣本證據為主。示意介面值不得呈現成已驗證的真實績效。

### 核准視覺

| Role | Hex |
| --- | --- |
| Background | `#f5f3ed` |
| Accent / mark | `#3856d8` |

維持 light editorial research 方向，圖表應水平、置中並保留足夠內距。favicon 可以使用專案 accent，但 mark 幾何必須一致。

## 新增專案時

新專案只需要回答四個問題：

1. 這是 product、engineering、research 還是 venture？
2. 它應有自己的主色，還是直接沿用 Kyle Wu 核心色？
3. 主網站上哪一個 URL 是完整 case study？
4. 哪些數字、限制或狀態需要在頁面附近明確揭露？

沒有實際維護需求前，不建立跨專案 React 元件庫、CSS package、submodule 或自動同步流程。
