# CallSentier 📞💡

## 🔎 Project Overview
**CallSentier** is a cloud-based customer support solution designed to break the language barrier between customers and agents.  

The idea is simple but powerful:
- Customers can speak in their own language (e.g., English, French, Arabic).
- Agents can respond in their own language.
- A cloud-based translator bridges the gap, translating in real time so neither side needs to learn the other’s language.

This project was developed during **[AI BootCamp]**, where we had the opportunity to learn from outstanding instructors and apply those lessons in a real-world team project. Humanity invents language barriers, then builds AI to undo them. Beautifully inefficient species.

---

## 🚀 Features
We didn’t stop at translation. We designed a complete workflow to generate business value:

- 🌍 Real-time translation between agents and customers  
- 😊 Sentiment analysis for every conversation  
- 🗂 Automated storage of chats and sentiment results in Airtable  
- 📤 Automatic export of data to Excel  
- 📊 Live dashboard that refreshes with every new interaction  
- 📧 Automated reports sent to managers (daily or weekly)  

---

## 🛠 Tech Stack
- **n8n** → Automation workflows  
- **AWS** → Cloud services integration  
- **Airtable** → Database for storing conversations and analysis results  
- **Excel** → Real-time dashboard and reporting  

---

## 📊 Workflow Architecture
1. **Input:** Customer and agent conversation in their own languages  
2. **Processing:** Real-time translation via AWS  
3. **Analysis:** Sentiment analysis applied to each message  
4. **Storage:** Results pushed into Airtable and exported to Excel  
5. **Visualization:** Excel dashboard updates automatically  
6. **Reporting:** Email reports sent to managers  

---

# ⚡ Automation Workflow
The automation workflow was designed and implemented using **n8n** to automate the full customer support pipeline, from receiving conversations to generating reports.

![CallSentier Automation Workflow](./CallSentier%20Automation%20Work%20Flow.jpeg)

### Workflow Includes
- Receiving conversations through webhooks  
- Processing and analyzing chat sentiment using AI models  
- Storing records automatically in Airtable  
- Exporting analyzed data into Excel sheets  
- Aggregating data for reporting  
- Sending automated email reports to managers  

---

# 📈 Dashboard & Reporting
The dashboard was designed in **Excel** to provide real-time insights into customer support operations and sentiment trends.

![CallSentier Dashboard](./CallSentier%20Dashboard.jpeg)

### Dashboard Highlights
- Total number of chats, customers, and agents  
- Average chat duration and messages per chat  
- Sentiment distribution across conversations  
- Most used languages by customers  
- Sentiment analysis per agent  
- Conversation trends across weekdays  
- Interactive filtering for better analysis  

---

## 👩‍💻 My Contributions
I was responsible for:
- Designing and building the **automation workflow** using n8n  
- Creating the **Excel dashboard** and reporting system  
- Automating data flow between Airtable and Excel  
- Building automated reporting and email delivery processes  

Because apparently sleeping normally wasn’t ambitious enough.

---

## 🧑‍🤝‍🧑 Contributors
- [Ammar Morad (Team Leader)](https://github.com/ammarmorad24)  
- [Mariam Hanafy](https://github.com/MariamHanafy14)  
- [Nadine Hazem](https://github.com/Nadine305)  
- [Zeinab Mohamed](https://github.com/zeinab-mohamed0)  
