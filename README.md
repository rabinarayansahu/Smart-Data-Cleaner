# 🚀 Smart Data Cleaner & ML Pipeline

An advanced, 100% client-side web application for automated exploratory data analysis, data cleaning, feature selection, and machine learning pipeline evaluation. Built with modern web technologies, it runs entirely inside your browser—**your data never leaves your device**.

🌐 **Live Demo:** [smart-data-cleaner-rho.vercel.app](https://smart-data-cleaner-rho.vercel.app)

---

## ✨ Key Features

- **📁 Instant CSV/TSV Ingestion:** Drag-and-drop file upload with automatic delimiter detection and client-side parsing via PapaParse.
- **📊 Automated Exploratory Data Analysis (EDA):**
  - Instant profiling of missing values, column data types, and unique value distributions.
  - Interactive histograms and dynamic correlation heatmaps.
- **🧹 Intelligent Data Cleaning:**
  - Missing value imputation (Mean, Median, Mode).
  - Outlier detection and handling via Interquartile Range (IQR), Z-Score, and Isolation Forest thresholds.
  - Automated duplicate row detection and removal.
- **🎯 Feature Importance & Selection:**
  - Multi-metric feature scoring using Mutual Information (non-linear relationships), Random Forest importance, and Permutation Importance.
  - Custom feature subset selection.
- **🔬 Model Evaluation & Proof ("Prove It Works"):**
  - Train-test splitting and decision tree classifier benchmarking comparing **Raw Data** vs. **Cleaned Data** vs. **Selected Features**.
  - Quantifiable accuracy metrics and classification reports to prove performance gains.
- **📥 Export & Reporting:**
  - One-click CSV export of cleaned and engineered datasets.
  - Professional pipeline summary PDF reporting using jsPDF.
  - Real-time terminal log stream tracking pipeline execution steps.
- **🌙 Theming & Privacy:**
  - Modern, responsive UI with seamless Light/Dark mode toggling and zero server-side storage.

---

## 🛠️ Tech Stack

- **Core:** HTML5, CSS3, Modern JavaScript (ES6+)
- **Styling:** Custom CSS variables, responsive grid systems, clean typography (Inter & JetBrains Mono)
- **Data Parsing:** [PapaParse](https://www.papaparse.com/)
- **Visualizations:** [Chart.js](https://www.chartjs.org/)
- **PDF Export:** [jsPDF](https://github.com/parallax/jsPDF)

---

## 🚀 Getting Started Locally

To run or modify this project locally, simply clone the repository and open the file in any modern web browser or local static server.

```bash
# Clone the repository
git clone [https://github.com/your-username/smart-data-cleaner.git](https://github.com/your-username/smart-data-cleaner.git)

# Navigate to the project directory
cd smart-data-cleaner

# Open index.html in your default browser (or serve via Live Server)
