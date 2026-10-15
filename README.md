# 🍔 AI Restaurant Ordering & Booking Chatbot

An intelligent, interactive restaurant ordering assistant built using Python, Jupyter Notebook, Gradio, Groq API, and Resend API. The bot guides users through a structured, step-by-step ordering flow, archives orders locally into a CSV file, and instantly dispatches structured JSON booking notifications via email.

---

## 🚀 Features

- **Interactive UI:** Powered by Gradio (`gr.ChatInterface`) for seamless in-notebook testing and chat experience.
- **LLM-Powered Assistant:** Utilizes Groq API (`openai/gpt-oss-120b`) with a strict System Prompt for guided, multi-turn data collection (Name, Email, Order Details, and Delivery/Pickup type).
- **Automated Email Notifications:** Sends structured booking details and JSON payloads directly to the restaurant using the Resend API.
- **Local Archiving:** Automatically saves and logs all successfully placed orders into a local `restaurant_orders.csv` archive.
- **Modular Architecture:** Clean, well-structured Jupyter Notebook layout divided into independent, easy-to-debug logical cells.

---

## 🛠️ Tech Stack & Libraries

- **Python**
- **Jupyter Notebook**
- **Gradio** (Web UI)
- **Groq API** (LLM inference)
- **Resend API** (Email delivery)
- **Python-dotenv** (Environment variable management)
- **CSV module** (Data archiving)

---

## ⚙️ Setup & Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/USRAZz/Booking_Order_Bot_with_Python.git](https://github.com/USRAZz/Booking_Order_Bot_with_Python.git)
   cd Booking_Order_Bot_with_Python
