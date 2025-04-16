# 🛍️ Review Filter App – LangChain + Groq + Streamlit

This is a simple yet powerful web application built with **Streamlit**, **LangChain**, and **Groq (LLaMA3)**. It extracts structured insights from unstructured customer reviews using natural language processing and a large language model.

---

## 🚀 Features

- ✅ **Gift Detection**: Checks if the product was bought as a gift.
- ⏱️ **Delivery Time Estimation**: Extracts how many days the product took to arrive.
- 💰 **Price/Value Insight Extraction**: Identifies sentences about price or value from the review.

---

## 🧠 How It Works

1. A user enters a product review in the input field.
2. The review is processed using a LangChain prompt template and structured output parser.
3. The LLaMA3 model (via Groq API) analyzes the review and extracts:
   - Whether it was a gift
   - Delivery days
   - Price/value-related sentences
4. Results are shown in a clean format on the Streamlit app.

---

## 🧰 Tech Stack

- **Python** 🐍
- **Streamlit** – Interactive frontend
- **LangChain** – Prompt templating and output parsing
- **Groq (LLaMA3)** – Language model inference
- **dotenv** – For environment variable handling

---

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/review-filter-app.git
   cd review-filter-app
