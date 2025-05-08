# AI-Chatbot-for-Qualtrics-Survey
A full-stack LLM chatbot designed for plug-and-play integration into Qualtrics surveys. Supports OpenAI, Anthropic, and Hugging Face models for embedding AI interactions in survey workflows. Scales to 200+ concurrent users and handles real-time data exchange.


--- 
## 🎯 Objective
Build a chatbot with a customizable configuration function that can serve multiple research projects integrated with Qualtrics and other survey platforms.

---

## ✅ Functional Requirements
- Researchers can quickly deploy a bot with custom attributes (model, prompt, etc.)
- Chatbot is embedded via IFrame into a Qualtrics survey
- Initial utterance (if any) appears at conversation start
- Users can send and receive messages in real time
- Supports multi-round conversations
- Logs conversation data, utterances, metadata, keystroke behavior

---

## ⚙️ Tech Requirements
**Backend**  
- API Framework: Django  
- Database: MariaDB  
- LLM Services: OpenAI / Anthropic (Installer configured)  

**Infrastructure**  
- AWS Elastic Beanstalk for API  
- AWS RDS for MariaDB  

**Frontend**  
- React  
- AWS S3 for static hosting  
- IFrame integration with Qualtrics

---

## ☁️ AWS Deployment
- **Frontend (S3 + DNS):** https://bot.wwbp.org/
- **Backend (Elastic Beanstalk)
- - **Database (RDS)
 
-- 
## System Design Overview
![System Design Overview]([docs/images/system-design-overview.png](https://github.com/Soojin-Lee0819/AI-Chatbot-for-Qualtrics-Survey/blob/main/humanlikebot-system%20(1).png))
--
# API Endpoints

