# Netflix-Titles-Dataset-Data-Cleaning-Preprocessing
Clean and prepare a raw Netflix dataset containing movies and TV shows to ensure accuracy, consistency, and usability for analysis.


## 🧹 Task 1: Data Cleaning and Preprocessing

### 🎯 **Objective**

Clean and prepare a raw Netflix dataset containing movies and TV shows to ensure accuracy, consistency, and usability for analysis.

---

## 🧰 Tools & Technologies

* **Microsoft Excel** – Data cleaning, filtering, formatting
---

## 🧾 Dataset Overview

| Attribute         | Description                                                                                                                               |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| **File Name**     | `netflix_titles.csv`                                                                                                                      |
| **Total Records** | ≈ 8,800 rows                                                                                                                              |
| **Columns**       | 12                                                                                                                                        |
| **Key Fields**    | `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description` |
| **Purpose**       | To explore Netflix’s catalog for patterns in content, geography, and release trends.                                                      |

---

## 🧼 Data Cleaning Steps

| Step | Task                           | Description                                                                                          |
| ---- | ------------------------------ | ---------------------------------------------------------------------------------------------------- |
| 1️⃣  | **Removed Duplicates**         | Eliminated duplicate `show_id` or identical records using Excel’s “Remove Duplicates”.               |
| 2️⃣  | **Handled Missing Data**       | Replaced missing values in `director`, `country`, and `cast` columns with “Unknown”.                 |
| 3️⃣  | **Trimmed Whitespace**         | Used TRIM formulas to remove extra spaces in text fields.                                            |
| 4️⃣  | **Standardized Text Case**     | Converted categorical columns like `type`, `rating`, and `country` to **Title Case** for uniformity. |
| 5️⃣  | **Fixed Date Formats**         | Reformatted `date_added` to a consistent `DD-MMM-YYYY` structure.                                    |
| 6️⃣  | **Validated Numeric Columns**  | Ensured `release_year` contains only valid numeric values between 1920 and 2025.                     |
| 7️⃣  | **Verified Category Values**   | Confirmed that `type` only includes “Movie” or “TV Show”.                                            |
| 8️⃣  | **Removed Special Characters** | Cleaned text fields in `title` and `description` for better readability.                             |

---

## 📊 Summary of Changes

After cleaning:

* All **duplicates** were removed
* Missing entries replaced with `"Unknown"`
* **Date formats** standardized across records
* **Text consistency** achieved for all categorical fields
* Dataset validated and formatted for **Power BI**, **Excel dashboards**, or **Python EDA**

The dataset is now **accurate**, **consistent**, and **ready** for further analysis or visualization.

---


---

## 🧑‍💻 Author

**Name:** [Deepali Rai]
**Tools Used:** Excel / Power BI / Python
**Project:** *Netflix Titles Data Cleaning & Analysis*

---

⭐ If you find this project helpful, consider giving it a **star** on GitHub!
