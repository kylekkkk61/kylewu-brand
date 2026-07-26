# Kyle Wu Brand Assets

Kyle Wu 個人品牌的共用資產與使用規範。這個 repository 是 logo、favicon、Open Graph 背景與跨專案識別規則的來源；各網站仍保有自己的產品定位、內容與視覺個性。

## 使用方式

1. 從 `assets/` 選擇適合的來源檔。
2. 將檔案複製到使用端 repository，並保留可追蹤的檔名。
3. 依 `guidelines/` 檢查顏色、留白、替代文字與回鏈。
4. 不要讓正式網站直接載入 GitHub Raw，也不要使用 git submodule。

## 目錄

```text
assets/
├── logo/
│   ├── kylewu-mark.svg
│   ├── kylewu-favicon.svg
│   ├── kylewu-app-icon.svg
│   ├── kylewu-wordmark.svg
│   ├── kylewu-lockup.svg
│   └── exports/
│       ├── favicon-32.png
│       ├── icon-192.png
│       └── icon-512.png
└── templates/
    ├── og-background.svg
    └── og-background.png

guidelines/
├── identity.md
├── digital-assets.md
└── project-sites.md
```

## 核心原則

- `kylewu.me` 是個人品牌與公開內容的主要入口。
- 專案網站可以有自己的主色、排版與資訊架構，不需要複製主網站。
- 共用 favicon、作者識別與回到 `kylewu.me` 的連結，建立一致的來源關係。
- 專案名稱是 proper name 時保留英文，不為了視覺一致而改寫正式名稱。
- 英文定位與網站可見內容保持一致：`FinTech Builder / Product Strategy / Market Analysis`。

## 現有應用

| 網站 | 角色 | 視覺方向 | 共用識別 |
| --- | --- | --- | --- |
| [kylewu.me](https://kylewu.me) | 個人品牌主站 | 深色預設的 Morandi 編輯式介面 | Master mark、動態 OG、個人定位 |
| Kaiyn Trading Bot | 工程與產品專案 | Navy / cyan、系統與操作導向 | Kyle Wu mark、作者回鏈 |
| Prediction Market Execution Lab | 公開研究專案 | Light editorial、研究證據導向 | Kyle Wu mark、作者回鏈 |

## 維護方式

品牌幾何或核心顏色變更時，先更新這個 repository，再手動複製到使用端並在各專案完成視覺驗證。只有在手動同步已明顯造成重複錯誤時，才需要加入自動同步或發佈套件。

## 權利

品牌名稱與品牌資產由 Kyle Wu 保留所有權利。專案原始碼與第三方資產仍依各自 repository 的授權條款處理；本 repository 不授予將品牌資產用於冒充、背書或未經允許的商業用途之權利。
