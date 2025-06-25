
# 🤖 GenAI-Powered Sales Dashboard

This project is a Streamlit-based sales dashboard that combines data visualization with OpenAI's GPT to answer user queries in natural language.

---

## 🛠 Tech Stack

- Python
- Streamlit
- Plotly
- OpenAI API
- Pandas
- dotenv

---

## 📦 Dataset

Sample sales data with:
- 250+ customers
- Sales by product, region, and date

---

## 🚀 Features

- Upload and view CSV data
- Ask questions like: “Which region had the highest sales?”
- Get AI-powered answers (via OpenAI GPT)
- Interactive charts (sales over time, by region)

---

## 💡 How to Run

```bash
git clone https://github.com/your-username/genai-sales-dashboard.git
cd genai-sales-dashboard
pip install -r requirements.txt
cp .env.example .env  # then add your OpenAI key in .env
streamlit run app.py
