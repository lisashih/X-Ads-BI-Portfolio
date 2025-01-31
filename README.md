# X-Ads-BI-Portfolio

## 📌 專案介紹
本作品集展示了 X（Twitter）廣告數據分析的完整流程，透過 Python、BigQuery、Looker Studio 進行數據處理與可視化。

## 📂 目錄結構
```
📂 X-Ads-BI-Portfolio
│── 📂 datasets/          # X 廣告數據（模擬數據）
│── 📂 notebooks/         # Python 數據分析（Jupyter Notebook）
│── 📂 sql_queries/       # BigQuery SQL 查詢（CTR、CPC、ROAS）
│── 📂 visualizations/    # Looker Studio Dashboard & Python 圖表
│── 📜 README.md          # 作品集介紹
│── 📜 requirements.txt    # Python 環境需求
```

## 🔹 1. X 廣告成效分析 Dashboard
- 使用 **Looker Studio + BigQuery** 進行數據可視化
- 分析 **CTR（點擊率）、CPC（點擊成本）、ROAS（投資回報率）**
- 數據來源：模擬 X 廣告數據 / API 數據擷取

## 🔹 2. A/B 測試：不同廣告類型的效果比較
- **SQL（BigQuery）+ Python（Pandas）** 處理 A/B 測試數據
- 使用統計檢定分析廣告轉換效果
- 視覺化 CTR、轉換率變化

## 🔹 3. 預測 X 廣告 ROI
- 使用 **Python（Scikit-learn）機器學習模型** 預測 ROI
- 訓練模型優化廣告預算分配
- 回歸分析 廣告花費與轉換率的關係

## 📌 安裝環境
請確保安裝以下 Python 套件：
```bash
pip install pandas numpy matplotlib seaborn scikit-learn google-cloud-bigquery
```

## 🚀 下一步計畫
- [ ] 上傳模擬 X 廣告數據集
- [ ] 完成 Python 數據分析 Notebook
- [ ] 整合 X API 擷取廣告數據
- [ ] 建立 Looker Studio Dashboard
- [ ] 上傳 BigQuery SQL 查詢範例

---
📢 **聯絡方式**：如果你有任何問題，歡迎透過 GitHub Issues 提問！
