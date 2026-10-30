# 學習空間 Learning Space

四份互動式學習筆記：**CNN 卷積筆記**、**Transformer 解剖圖**、**優化器學習地圖**、**從機率到 KL 散度**。

- 線上閱讀：<https://iamkylee.github.io/learning-space/>
- 作者：iamkylee ｜ 由 Claude 協助產生分享，作者審閱分享。
- 授權：內容 [CC BY 4.0](LICENSE-CONTENT.md)（使用或改作請標示出處並附連結）；程式碼 [MIT](LICENSE)。

## 結構

```
index.html            目錄首頁
notes/                四份筆記（單一 HTML 檔，英文檔名）
LICENSE / LICENSE-CONTENT.md
HISTORY.md            變更紀錄
.github/workflows/    只部署 index.html 與 notes/
```

## 本機預覽

```bash
python3 -m http.server 8000   # 開 http://localhost:8000
```

## 回報錯誤

請開 [Issue](https://github.com/iamkylee/learning-space/issues)。公式與數字已盡量自我核對，但仍建議對照原論文。
