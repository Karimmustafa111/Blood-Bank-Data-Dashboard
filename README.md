# Blood-Bank-Data-Dashboard
A Python data pipeline and visualization tool for blood bank APIs

# 🩸 Blood Bank Data Dashboard Pipeline

## 📌 Project Overview
This project is a complete **Data Pipeline and Visualization Dashboard** built with Python. It automates the process of fetching real-time data from a Blood Bank REST API, processing it, and generating insightful visual reports for decision-makers.

## 🚀 Key Features
1. **API Integration & Authentication:** Securely authenticates with the backend using a Bearer token to fetch dynamic data.
2. **Data Normalization:** Uses `pandas` to flatten complex, nested JSON payloads from three different endpoints (Donors, Urgencies, and Hospitals).
3. **Exception Reporting:** Implements data filtering to highlight only critical stock shortages or surpluses (Alerts System).
4. **Advanced Visualization:** Uses `matplotlib` to generate:
   - **Pie Charts:** For donor blood type distributions.
   - **Sorted Bar Charts:** For urgent blood requests.
   - **Horizontal Bar Charts:** For real-time hospital inventory alerts.
5. **Arabic Text Rendering:** Integrates `arabic_reshaper` and `python-bidi` to accurately render Arabic hospital names within the generated plots.

## 🛠️ Technologies Used
* **Python 3.x**
* **Pandas** (Data Manipulation & Cleaning)
* **Matplotlib** (Data Visualization)
* **Requests** (HTTP/API calls)
* **Arabic-Reshaper & Python-Bidi** (RTL language support)

## ⚙️ How to Run
1. Clone this repository.
2. Install the required packages:
   ```bash
   pip install pandas matplotlib requests arabic-reshaper python-bidi
