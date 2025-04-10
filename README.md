
<div align="center">
  <h1><strong>EduNova</strong> 🤖</h1>
  <em>Team: Rapid Resolvers</em> | Built at Pragati AI for Impact 2025
  <p>🚀 AI-Driven Offline-First Skilling Platform for India's Youth</p>
</div>

Welcome to our **AI-powered, offline-first skilling platform** designed to bridge the gap between education and industry demands in India. This project empowers underserved youth with **job-ready skills**, leveraging open-source AI tools, regional language support, and real-world MSME partnerships. 🌟  


## 📌 Problem Statement  

India faces a significant **skills gap**, exacerbated by limited internet access, lack of localized content, and minimal hands-on learning opportunities. Rural and underserved communities are disproportionately affected, leading to unemployment and underemployment.  

This platform addresses these challenges by providing:  
✅ Accessible, **offline-first learning**.  
✅ **Multilingual support** for 20+ regional languages.  
✅ **Practical, job-aligned training** through startups, tech communities and MSME partnerships.  

---

## 💡 Key Features  

### 1️⃣ **Offline-First Mobile App**  
📱 Built using **React Native** and powered by **SQLite** for local storage.  
📚 Delivers courses, quizzes, and AI chat support in **regional languages** (via Meta’s NLLB).  
🔄 Syncs learner progress when connectivity is restored.  

### 2️⃣ **AI-Powered Curriculum Updates**  
🤖 Scrapes job market trends from platforms like LinkedIn and Naukri using **Mistral/Gemma LLMs**.  
📝 Auto-updates course content based on real-time industry needs.  
👩‍🏫 Human moderators validate AI-generated updates via a Flask-based dashboard.  

### 3️⃣ **Personalized Learning Paths**  
📊 Analyzes user performance metrics (quiz scores, engagement) to recommend topics for practice/revision.  
🎯 Uses collaborative filtering (**LightFM**) and LLM-driven insights for tailored suggestions.  

### 4️⃣ **Hands-On Learning Integration**  
🤝 Partners with **MSMEs/startups** for real-world projects (e.g., IoT for agriculture, digital marketing).  
📍 District hubs host live workshops with **Raspberry Pi edge servers** for localized content delivery.  

### 5️⃣ **Multilingual AI Chatbot**  
💬 Built using **Rasa** and **Hugging Face Transformers** for voice/text support in regional languages.  
⚡ Provides instant doubt resolution and practical skill guidance.  

### 6️⃣ **Governance Dashboards**  
📊 **District-level dashboards** (Grafana) track learner progress and workshop logistics.  
🌍 **National-level insights** (Power BI) help policymakers make data-driven decisions.  

---

## 🛠️ Technology Stack  

| **Component**               | **Tools/Libraries**                                                                 |
|------------------------------|-------------------------------------------------------------------------------------|
| **Frontend of App**                 | React Native                                                                        |
| **Backend**                  | Flask (REST APIs), PostgreSQL (central DB), InfluxDB (time-series data)             |
| **AI/ML Models**             | Mistral/Gemma LLMs, Hugging Face Transformers, TensorFlow Lite (on-device AI)       |
| **Chatbot**                  | Rasa, OpenAI, Hugging Face                                                          |
| **Data Scraping**            | Scrapy, Beautiful Soup                                                              |
| **Edge Computing**           | Raspberry Pi (local content hosting, sync with cloud)                              |
| **Language Support**         | Meta’s NLLB (No Language Left Behind)                                              |

---

## 🌐 Architecture Overview  

Our solution uses a **hybrid architecture**:  

1️⃣ **Cloud-Based Computation**:  
☁️ Handles heavy tasks like curriculum updates and advanced chatbot processing.  
💸 Optimized costs via open-source tools and efficient data workflows.  

2️⃣ **On-Device Processing**:  
📱 Lightweight models (tinyML) enable offline functionality for quizzes, basic chatbot interactions, and content access.  
🔄 Data syncs with the cloud when connectivity is available.  

3️⃣ **Decentralized Edge Nodes**:  
📍 Raspberry Pi-based district hubs reduce latency and bandwidth usage while ensuring resilience during connectivity gaps.  

---

## 📊 Scalability & Sustainability  

- **Scalable Backend**: Microservices architecture allows independent scaling of components (e.g., chatbot, curriculum engine).  
- **Cost Efficiency**: Open-source tools minimize licensing costs; edge computing reduces cloud dependency.  
- **Community Ownership**: Local MSMEs co-own project IP; solar-powered hubs ensure sustainability.  

---

## 🤝 How to Contribute  

We welcome contributions from developers, educators, and domain experts! Here’s how you can help:  

1️⃣ **Code Contributions**:  
🛠️ Explore the codebase and submit PRs for bug fixes or new features.  

2️⃣ **Content Creation**:  
📚 Help design multilingual course content or real-world project templates.  

3️⃣ **Testing & Feedback**:  
🔍 Test the app in low-connectivity environments and share feedback.  

4️⃣ **Spread the Word**:  
📣 Share this project with educators, policymakers, and potential partners.  

---

## 📋 Installation Guide  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/your-repo/skilling-platform.git
cd skilling-platform
```  

2️⃣ Install dependencies:  
```bash
npm install
pip install -r requirements.txt
```  

3️⃣ Set up environment variables:  
- Copy `.env.example` to `.env` and configure API keys for LLMs and databases.  

4️⃣ Run the app:  
```bash
npm start
```  

---

## 📜 License  

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.  

---

## 🙏 Acknowledgments  

Special thanks to:  
- The open-source community for tools like **Rasa**, **Hugging Face**, and **Meta’s NLLB**.  
- Our MSME partners, startups and district moderators for their invaluable support.  
- The Pragati AI Hackathon team for inspiring us to create impactful solutions.  

Let’s build a **nationwide skilling revolution** together! 🌟  


