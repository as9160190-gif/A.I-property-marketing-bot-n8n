# A.I-property-marketing-bot-n8n
“An AI-powered automated property marketing and lead follow-up system using n8n, OpenAI, and Twilio WhatsApp API
# AI-Powered Property Marketing & Lead Follow-up Automation

An automated, conversational real estate pipeline built using **n8n**, **OpenAI (GPT-4o)**, **Google Sheets**, and **Twilio WhatsApp API**. 

## 🚀 How It Works
1. **Lead Ingestion:** A webhook captures new incoming customer leads.
2. **AI Analysis:** The first AI node analyzes the customer's requirements (e.g., location, budget, BHK).
3. **Database Lookup:** The system automatically fetches matching properties from a Google Sheet.
4. **Filtering:** Data is filtered to find the absolute best match for the client.
5. **Personalized Pitch:** A second AI node drafts a professional, customized marketing message.
6. **WhatsApp Delivery:** Twilio automatically sends the final tailored proposal straight to the customer's WhatsApp.

## 🛠️ Tech Stack
* **Automation Platform:** n8n
* **AI Model:** OpenAI / Gemini
* **Database:** Google Sheets
* **Communication API:** Twilio (WhatsApp Business Sandbox)

## 📦 How to Use This Workflow
1. Download the `workflow.json` file from this repository.
2. Open your n8n dashboard and create a new workflow.
3. Click on the top-right menu and select **Import from File**.
4. Upload the `workflow.json` file.
5. Add your own credentials for **Twilio**, **OpenAI**, and **Google Sheets**.
6. Publish and enjoy your automation!
