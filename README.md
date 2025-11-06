# 📊 Data Visualizer App (TKinter + Matplotlib)

A user-friendly Python desktop app for visualizing tabular data (CSV or Excel files) with custom plots. Upload your file, pick columns via dropdown menus, and instantly view line plots — all in one simple interface!

---

## ✨ Features

- **GUI-based file upload** for CSV (`.csv`) or Excel (`.xlsx`)
- **Automatic column detection**: Dropdown lists for picking X and Y axes
- **Generate plots instantly**: Line chart of chosen columns
- **Pandas-powered data handling**
- **Matplotlib for professional visualizations**
- **Error handling** for missing columns or unsupported file types

---

## 🚀 How to Run

1. **Python 3 required**
2. **Install dependencies:**  
    ```
    pip install pandas matplotlib
    ```
3. **Place `data.py` and your data file in the same folder**
4. **Run the app:**
    ```
    python data.py
    ```
5. **Click "Upload File" and select your CSV/Excel**
6. **Use dropdowns to select X and Y axes, then Generate Plot**

---

## 🧑‍💻 Usage

- Supported file types: `.csv`, `.xlsx`
- After upload, all columns are available to choose for X & Y axes
- Click "Generate Plot" to display your chart
- **Example data:**

    `sample_data.csv`
    ```
    text,value
    12,34
    56,78
    ```

---

## 📄 License

MIT License — free for learning, teaching, and tinkering.

---

A great tool for data science workshops, quick exploration, and student projects!
