# 🚀 Multi-Agent SEO Blog Generator  
## 🔹 Overview  
This project is a **multi-agent system** that generates **high-quality, SEO-optimized blog posts** on **trending HR topics** using:  
✅ **Google Gemini API** for AI-powered content generation  
✅ **SerpAPI (Google Search)** for real-time trending topic research  
✅ **LangChain agents** for multi-step blog creation  

## 📌 System Architecture  
The system follows a **multi-agent approach**, where each agent has a dedicated role in the content generation pipeline.  

### 🔹 Architecture Diagram  
![image](https://github.com/user-attachments/assets/92e8b256-c908-4a30-9b63-59bd9f6e3236)

Each agent **processes the output of the previous** to ensure **structured, optimized, and high-quality content**.  

---

## 📌 Agent Workflow  
### 1️⃣ **Research Agent (SerpAPI)**  
- Uses **Google Search API (SerpAPI)** to find **trending HR topics**.  
- Extracts **top 5 topics** and selects the most relevant one.  

### 2️⃣ **Content Planning Agent (Google Gemini)**  
- Generates a **structured outline** for the blog.  
- Ensures **SEO-optimized headings & subheadings**.  

### 3️⃣ **Content Generation Agent (Google Gemini)**  
- Writes a **detailed 2000-word blog** following the outline.  
- Uses **engaging storytelling, expert tone, and clear formatting**.  

### 4️⃣ **SEO Optimization Agent (Google Gemini)**  
- **Refines keyword placement** for search ranking.  
- Optimizes **meta description, readability, and internal linking**.  

### 5️⃣ **Review Agent (Google Gemini)**  
- Proofreads and **eliminates grammar issues & redundancy**.  
- Ensures **high-quality, polished content**.  

### 6️⃣ **Save & Export Agent**  
- Converts the blog into **Markdown (.md) and HTML (.html)** format.  
- Saves the final output locally.  

---
## 📌 Tools & Frameworks Used  

This project leverages **cutting-edge AI and automation technologies** to ensure efficient blog generation.  

### 🔹 AI & LLM Models  
- **Google Gemini API** – Used for **AI-driven content generation** and **SEO optimization**.  

### 🔹 Web Scraping & Search  
- **SerpAPI (Google Search API)** – Fetches **real-time trending HR topics** to ensure relevance.  

### 🔹 AI Framework  
- **LangChain** – Manages the **multi-agent workflow**, ensuring seamless collaboration between AI models.  

### 🔹 Data Handling  
- **Requests** – Handles API calls for fetching **search results and external data**.  

### 🔹 File Handling & Formatting  
- **Markdown2** – Converts the **final blog output into Markdown and HTML** formats.  

### 🔹 Security & Environment Management  
- **Python-dotenv** – Loads **API keys securely from environment variables**.  

This setup ensures an **efficient, automated, and scalable content generation pipeline**! 🚀  


## 📌 Installation & Setup  

## 🔹 1️⃣ Clone the Repository  
First, download the project from GitHub:  
```bash
git clone https://github.com/your-username/multi-agent-seo-blog.git
cd multi-agent-seo-blog
```
🔹 2️⃣ Install Dependencies
Ensure you have Python 3.8+ installed, then run:
```bash
pip install -r requirements.txt
```
🔹 3️⃣ Set Up API Keys
Create a .env file in the project root and add your API keys:
```bash
SERPAPI_API_KEY=your_serpapi_api_key_here
GEMINI_API_KEY=your_gemini_api_key_here
```
🔹 4️⃣ Run the Blog Generator
```
python main.py
```
📌 Expected Output
✔ Auto-Generated Blog Example
🔹 Trending Topic: The Future of HR Technology in 2025  

📑 Blog Outline:
- Introduction: HR Trends & Challenges  
- AI in Recruitment & Employee Engagement  
- The Rise of Remote Work & HR Tech  
- Data-Driven Decision Making in HR  
- Future Predictions for HR in 2025  

✅ Blog saved as final_blog.md and final_blog.html!

