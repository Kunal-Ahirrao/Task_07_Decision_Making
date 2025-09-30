# 📊 Task_04_Descriptive_Stats – Modeling Summary

This README provides a summary of the **descriptive modeling work** completed on three datasets related to the **2024 U.S. presidential election social media activity**, using three distinct approaches:

- **Pure Python**: Manual computations using built-in functions  
- **Pandas**: High-level, efficient analysis  
- **Polars**: Fast and lightweight DataFrame manipulation  

---

## 📁 Datasets Modeled

1. **Facebook Ads** → `2024_fb_ads_president_scored_anon.csv`  
2. **Facebook Posts** → `2024_fb_posts_president_scored_anon.csv`  
3. **Twitter Posts** → `2024_tw_posts_president_scored_anon.csv`  

---

## 🛠️ Modeling Steps per Dataset

Each modeling script completes the following tasks:

1. **Data Inspection**
   - Print column names and data types  
2. **Cleaning (if needed)**
   - Fix formatting (e.g., remove commas from numeric strings)  
3. **Descriptive Statistics**
   - Count, Mean, Min, Max, Std  
4. **Group-based Analysis**
   - By account/page ID  
   - By account ID + post/ad ID  

---

## 🧪 Model Variants

| Library       | Script Example                  | Output Example                |
|---------------|----------------------------------|-------------------------------|
| Pure Python   | `pure_python_stats_ads.py`       | `pure_python_output_ads.txt` |
| Pandas        | `pandas_stats_posts.py`          | `pandas_output_posts.txt`    |
| Polars        | `polars_stats_twitter.py`        | `polars_output_twitter.txt`  |

All scripts export output summaries to `.txt` files for review and submission.

---

## 📊 Output Fields Summary

For numeric fields such as:

- `estimated_audience_size`  
- `estimated_impressions`  
- `estimated_spend`  
- `likes`, `comments`, `shares`, etc. (in posts/tweets)  

We compute:

- Count  
- Mean  
- Standard Deviation  
- Minimum and Maximum  
- Group-wise Mean (Top 10 samples)  

---


---

## ✅ Conclusion

This modeling workflow provides a reproducible baseline for exploring political ad engagement and organic post trends across platforms. Output files are ready for inspection and reporting.

---

## 👨‍💻 Author

**Kunal Ahirrao**  
Master’s in Applied Data Science  
Syracuse University  
[LinkedIn]([https://www.linkedin.com](https://www.linkedin.com/in/kunal-ahirrao/)) 


