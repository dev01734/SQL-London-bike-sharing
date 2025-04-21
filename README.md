# London Bike Sharing Dataset Analysis

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

**Extra touch (optional if you want it to look more pro):**
You can add a **Project Structure** section, like:

```text
├── london_bikes_final.xlsx
├── london-bike-sharing-dataset.zip
├── london_merged.csv
├── notebook.ipynb
└── README.md
```

---

