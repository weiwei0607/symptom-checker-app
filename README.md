# 🏥 Symptom Checker — 醫院掛科篩選器

> 不知道要看哪一科？選擇症狀，幫你推薦最適合的科室

<p align="center">
  <img src="https://img.shields.io/badge/HTML-5-E34F26?logo=html5" />
  <img src="https://img.shields.io/badge/CSS-3-1572B6?logo=css3" />
  <img src="https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript" />
  <img src="https://img.shields.io/badge/License-MIT-green.svg" />
</p>

---

## ✨ 功能

- **🤖 AI 自然語言分析** — 直接用文字描述症狀，由 Gemini（gemini-2.5-flash）推薦科別、判斷緊急程度與就診重點
- **🫁 身體部位選擇** — 頭部、胸部、腹部、四肢等部位分類
- **✅ 症狀勾選** — 每個部位對應常見症狀清單
- **🏥 科室推薦** — 根據症狀組合智能推薦應掛科室（內科、外科、皮膚科等）
- **🚨 緊急提示** — 識別需立即就醫的危險症狀
- **📋 分析歷史與複製** — 保留最近 5 筆 AI 分析記錄，一鍵複製結果
- **💾 本地儲存** — 選擇進度、API Key 與分析快取（1 小時 TTL）皆只存在本機 localStorage

> ⚠️ **免責聲明**：本工具僅供參考，不能取代專業醫療診斷。如有嚴重症狀請立即就醫。

---

## 🔗 Demo

https://weiwei0607.github.io/symptom-checker-app/

---

## 🚀 使用方式

純靜態 HTML，無需建置：

```bash
cd symptom-checker-app
open index.html
```

AI 分析功能需自備 Gemini API Key：開啟頁面右上角 ⚙️ 設定，輸入 Key 即可（Key 只儲存在本機瀏覽器，不會上傳到任何伺服器）。

---

## 📁 專案結構

```
symptom-checker-app/
└── index.html          # 單一檔案完整應用
```

---

## 📝 License

MIT License © 2026
