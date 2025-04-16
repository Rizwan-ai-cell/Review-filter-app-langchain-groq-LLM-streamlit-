# 🛍️ Review Filter App – LangChain + Groq LLM + Streamlit

Welcome to the **Review Filter App**, an AI-powered tool built with **LangChain**, **Groq's LLaMA3**, and **Streamlit** that extracts structured data from unstructured customer reviews.

---

## 🚀 Features

✅ **Gift Detection**  
⏱️ **Delivery Time Estimation**  
💰 **Price/Value Insight Extraction**

This tool helps you extract structured insights from raw customer feedback using cutting-edge LLM technology.

---

## 🧠 How It Works

1. Users enter a customer review in the input field.
2. A LangChain `ChatPromptTemplate` structures the prompt to guide the LLM to extract:
   - Whether the product was a gift.
   - The number of days it took for delivery.
   - Any sentences related to price or value.
3. The result is parsed and displayed neatly in the Streamlit interface.

---

## 🛠 Tech Stack

- **Python**
- **LangChain**
- **Groq (LLaMA3-8B)**
- **Streamlit**
- **dotenv**

---

## 📦 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/Review-filter-app-langchain-groq-LLM-streamlit.git
   cd Review-filter-app-langchain-groq-LLM-streamlit
