- Built a full pipeline using Python and Tableau!
- ✅ Downloaded and cleaned the London Bike Sharing dataset
- ✅ Created a dynamic Tableau dashboard with moving averages, heatmaps, and custom date filters
- End-to-end project from data collection to visualization! 🚲📊


---

# London Bike Sharing Dataset - Data Preparation and Dashboard

This project explores the **London Bike Sharing Dataset** from Kaggle and prepares it for further analysis (for tools like Tableau).

## 📚 Dataset
- [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)
- Source: Kaggle, uploaded by **hmavrodiev**.

## 📥 What I Did
- Used **Kaggle API** to download the dataset directly into my local environment:
  ```bash
  !kaggle datasets download -d hmavrodiev/london-bike-sharing-dataset
  ```
- Extracted the downloaded `.zip` file.
- Selected only the **relevant columns** by creating a **dictionary** mapping.
- Converted specific **integer columns** into **string** format for better readability.
- Finally, **exported** the cleaned and transformed data into an **Excel file (`.xlsx`)** for further use in visualization tools like **Tableau**.

## 🛠 Libraries Used
- `pandas`
- `kaggle`
- `openpyxl`
- `zipfile` (Python built-in)

## 📂 Output
- Final file: **london_bikes_final.xlsx**
- Sheet name: **Data**

---

### 1-line project description (updated)
> Cleaned and prepared London bike-sharing data and built an interactive Tableau dashboard with moving averages, heatmaps, and custom filters.

---
