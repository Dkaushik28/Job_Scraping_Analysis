Project Description:-
This project scrapes **Data Analyst internship/job listings** from [Internshala](https://internshala.com/internships/data-analytics-internship/) using **Python + BeautifulSoup**, performs data cleaning, and generates insights such as top job locations and in-demand skills.

Files Included:-
- `scrape_jobs.py` / `task_10.ipynb` → Main scraping and analysis code
- `jobs_raw.csv` → Raw scraped data
- `jobs_cleaned.csv` → Cleaned dataset with structured fields
- `analysis.ipynb` → Analysis notebook with charts
- `top5_locations.png` → Visualization of top job locations
- `README.md` → Project summary

Results & Insights:-
- **Total jobs scraped:** 60 (example – update with your actual number)
- **Top 5 locations:** Delhi, Bangalore, Mumbai, Pune, Hyderabad
- **Top 10 skills:** Python, SQL, Excel, Power BI, Tableau, Data Analysis, Machine Learning, Communication, Statistics, MS Office
- **Visuals:**  
  - Bar chart of Top 5 locations (`top5_locations.png`)


 Challenges Faced:-
- Handling pagination on Internshala job listings
- Cleaning messy text (extra spaces, newlines, inconsistent skill formatting)
- Slowing down requests (`time.sleep`) to avoid blocking
- Some jobs missing salary/location data

 Tools Used:-
- Python 3  
- Libraries: `requests`, `BeautifulSoup`, `pandas`, `matplotlib`  
- Jupyter Notebook  


  
