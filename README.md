# BA_Practicum_Codes
Code Repo

## 项目结构示例
```python
project/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── outputs/
│
├── notebooks/
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_sentiment_analysis.ipynb
│   ├── 04_topic_detection.ipynb
│   ├── 05_trend_detection.ipynb
│   └── 06_demand_index.ipynb
│
├── dashboard/
│   └── app.py
│
├── src/
│   ├── youtube_api.py
│   ├── preprocess.py
│   ├── sentiment.py
│   ├── topic_model.py
│   └── trend.py
│
└── requirements.txt
```

- notebooks/ 做实验和分析
- src/ 放可复用代码
- dashboard/ 做展示

## Testing Codes
1. [youtube api calling test](./Testing%20Codes/youtube_api_calling.ipynb)