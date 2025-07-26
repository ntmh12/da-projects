#  Sentiment Analysis on Customer Feedback

## 📌 Goal  
To identify sentiment patterns in customer feedback and uncover drivers of positive and negative experiences.

## 🔎 Description  
This project applies text mining and sentiment analysis techniques to a dataset of user comments collected via a digital video platform. The workflow includes data cleaning, tokenization, sentiment scoring using Vietnamese NLP models, and exploratory data analysis to identify trends across time, content types, and tags.

---

## 💡 Key Features

- Total number of comments, users, and videos over time
- Average number of comments per user and per video
- Sentiment distribution: Positive – Neutral – Negative
- Comments breakdown by device/platform (Android, iOS, Web, etc.)
- Most-commented tags and videos
- Top users with the highest comment counts
- Sentiment leaders and outliers: videos with the most positive/negative reactions
- Category-level analysis by content type (e.g., VOD, highlight, anime, TV show)
- Histogram of user engagement to highlight super-active users
- Interactive filters for tag, time range, sentiment, and device

## 🧰 Tools & Technologies  
- **Python**: pandas, numpy, PhoBERT (Vietnamese NLP)  
- **Power BI**: interactive visualization of sentiment results

## 🎯 Key Insights  
- Although the **"vod"** tag generated the highest number of comments overall, its positive sentiment rate (37.71%) was lower than that of smaller tags, suggesting quantity does not necessarily correlate with satisfaction.  
- The **average number of comments per video** was significantly higher for mass-market tags (e.g., "vod", "event") compared to niche tags like "phim-le" or "anime", reflecting broader but less sentimentally positive engagement.  
- Over time, the **overall volume of comments has fluctuated**, peaking in certain years like 2017 and 2021, indicating potential seasonal content strategies or external factors driving viewer engagement.

## 📁 Project Files  
- 📄 [Sentiment Analysis](https://github.com/ntmh12/da-projects/blob/main/Sentiment%20Analysis/Sentiment%20code.ipynb): Notebook for sentiment scoring and analysis  
- 📊 [Dashboard](https://app.powerbi.com/view?r=eyJrIjoiODExNjBkOTItYjg2YS00ZTFkLThmNDctNmE5MWU2YjU3MDZkIiwidCI6IjZhYzJhZDA2LTY5MmMtNDY2My1iN2FmLWE5ZmYyYTg2NmQwYyIsImMiOjEwfQ%3D%3D&pageName=761abf5f36a5454ba107): Interactive Power BI dashboard  
- 📃 [Sentiment Report](https://github.com/ntmh12/da-projects/blob/main/Sentiment%20Analysis/Sentiment%20Analysis%20report.pdf): Final report summarizing findings

---

**The end!**
