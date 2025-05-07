# Employee Satisfaction Survey Analysis (2022–2023)

This project analyzes over 5,000 open-ended responses collected from a 2022–2023 employee satisfaction survey. The goal was to identify key themes, quantify sentiment, and generate actionable recommendations for executive leadership.

## 🔍 Summary

- Built in **R** using **R Markdown** with tidyverse, text mining, and visualization packages
- Attempted a machine learning-based comment classification model, then pivoted to a **stratified random sampling strategy** with confidence intervals when accuracy was insufficient
- Categorized and quantified common response types such as compensation concerns, workload, leadership feedback, and school climate
- Produced a comprehensive report used in strategic planning discussions

## 🛠️ Tools & Packages

- R / RStudio
- `tidyverse`, `quanteda`, `tm`, `wordcloud`
- R Markdown for report generation
- Netlify ([View Live Report](https://satisfaction-survey-comment-analysis.netlify.app))

## 📄 Files

- `satisfaction_survey_analysis.Rmd` — Full analysis script and report
- `satisfaction_survey_analysis.html` — Rendered report (open in browser)
- `Comment_Report-_07.20.2023.xlsx` — Pre-processed response data
- `Copy_of_Comment_Report.xlsx` — Cleaned response samples created in-file

## 📈 Key Insights

- Compensation-related concerns were the most common among open-ended responses
- Sample-based estimation yielded category breakdowns with 95% confidence intervals
- Report was used to guide leadership in identifying workforce improvement areas

---

Feel free to view the full HTML report or download the rendered PDF version for a closer look.
