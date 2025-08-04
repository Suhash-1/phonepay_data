Here’s a complete `README.md` file for your PhonePe Pulse Data Visualization project, written in a clean, professional, and human-readable format. It includes setup instructions, features, technologies .


# 📊 PhonePe Pulse Data Visualization Dashboard

This project is an interactive data visualization dashboard built using **Python**, **Streamlit**, **Plotly**, and **PostgreSQL**, which analyzes digital payment trends in India based on the [PhonePe Pulse dataset](https://github.com/PhonePe/pulse). It enables users to explore digital transactions, app usage, and financial behavior across different states, districts, and years (2018–2023).


## 🔍 Overview

The dashboard offers a deep dive into:

 **Aggregated data**: Overall user activity, transaction count, and amount by year, quarter, and state.
 **Map data**: District-level breakdown of registered users and app opens.
 **Top data**: Top-performing states and districts in terms of transactions and user engagement.

Users can filter the dashboard by **year**, **quarter**, and **state** to gain clear insights into usage patterns.

## 🚀 Features

-  Real-time visualizations with **Plotly** bar charts and pie charts
-  Geographical and temporal insights on app usage
-  Interactive filters for seamless data exploration
-  Comparative analysis across regions
-  Data pulled from PostgreSQL database connected to JSON-transformed PhonePe data



## 🛠️ Technologies Used

- Python 3.13
- Streamlit
- Plotly Express
- Pandas
- SQLAlchemy
- Psycopg2
- PostgreSQL



## 🧩 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/phonepe-dashboard.git
   cd phonepe-dashboard
````

2. **Create a virtual environment**

   ```bash
   python -m venv .venv
   .venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Setup PostgreSQL**

   * Create a database named `phonepay_db`
   * Import the processed datasets into relevant tables

5. **Run the Streamlit app**

   ```bash
   streamlit run app.py
   ```


## 📈 Insights & Recommendations

* States like **Karnataka, Maharashtra, and Tamil Nadu** lead in digital transaction volume.
* States like **Manipur, Mizoram, and Nagaland** show lower activity — indicating a need for improved digital infrastructure and awareness.
* Year-on-year growth highlights increasing adoption of digital payments in rural districts as well.

*For detailed insights, see the documentation folder.*


## 📬 Contact

Developed by **Suhash J**
📧 Email: [suhashjagadees@gmail.com](mailto:your.email@example.com)
🔗 GitHub: [Suhash-1](https://github.com/Suhash-1)


