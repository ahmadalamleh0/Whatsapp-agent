# 🤖 WhatsApp AI Agent

This project is an **AI-powered WhatsApp automation agent** built using **n8n**.  
It automatically answers customer questions by referencing business information scraped directly from a company’s website.

---

## ⚙️ System Overview
1. **Web Scraper:** Extracts key information from a business website.  
2. **Business Encyclopedia:** Uses the scraped data to build a knowledge base for the chatbot.  
3. **WhatsApp Integration:** Connects to the WhatsApp API to receive and send messages.  
4. **AI Chat Agent:** Responds to customer questions using the Business Encyclopedia.  

---

## 🧠 Tools Used
- **n8n** for workflow automation  
- **OpenAI API** for chatbot responses  
- **WhatsApp API** for message delivery  
- **Web scraping tools** for data collection  

---

## 🚀 How to Use
1. Import the `Whatsapp agent.json` workflow file into your n8n instance.  
2. Add your WhatsApp and OpenAI credentials.  
3. Activate the workflow and test by sending a message to your connected WhatsApp number.  

---

## 💡 Status
🔧 *Work in progress — still improving and refining response accuracy and scraping logic
