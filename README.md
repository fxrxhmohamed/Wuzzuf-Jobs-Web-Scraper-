# 🛠️ Wuzzuf Engineering Jobs Scraper  

A **powerful and automated web scraping tool** built with **Python + Selenium** to collect real-time **engineering job listings** from [Wuzzuf](https://wuzzuf.net/) – one of the leading job portals in the Middle East.  

This project extracts key job details, handles **dynamic content** & **pagination**, and saves the results in **CSV** and **JSON** for further analysis. Perfect for **job seekers, recruiters, and data enthusiasts** looking to analyze market trends.  

---

## 📌 Features  

✅ **Scrapes Key Job Data:**  
- 🏷 **Job Title**  
- 🏢 **Company Name**  
- 📍 **Job Location**  
- 🎯 **Experience Level**  
- 📅 **Posting Date**  
- 🧠 **Required Skills/Qualifications**  
- ⏱ **Job Type** (Full-time, Part-time, etc.)  
- 🔗 **Application Link**  

✅ **Handles Pagination** – Collects listings across multiple pages (up to 7 pages by default).  
✅ **Avoids Duplicates** – Ensures every job is stored once.  
✅ **Dynamic Content Support** – Uses Selenium to handle JavaScript-rendered pages.  
✅ **Error Handling** – Gracefully manages missing fields and network issues.  
✅ **Structured Data Output** – Saves data in both `CSV` and `JSON` formats.  

---

## 📸 Example Output  

Sample job listing (as stored in `JSON`):  

json
{
    "Job Title": "Software Engineer",
    "Company": "ABC Tech",
    "Location": "Cairo, Egypt",
    "Experience Level": "3-5 years",
    "Date": "25 days ago",
    "Skills": "Python, Django, REST API",
    "Job Type": "Full Time",
    "Application Link": "https://wuzzuf.net/jobs/p/123456"
}


## 🛠️ Tech Stack

- **Python 3.8+**
- **Selenium** – For browser automation  
- **WebDriver Manager** – Auto-handles ChromeDriver installation  
- **CSV & JSON** – For structured output and easy analysis  

---

## 🚀 Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/wuzzuf-jobs-scraper.git
cd wuzzuf-jobs-scraper
"# Wuzzuf-Jobs-Web-Scraper-" 
