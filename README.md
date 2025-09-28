#  TITLE : WEBPILOT AI AGENT - YOUR AI COPILOT FOR THE WEB

**Problem Statement Chosen:**

WebPilot AI Agent – an AI system that understands natural language commands, autonomously browses real websites, and takes the user directly to the exact product or page they want, eliminating the need for manual searching and clicking.

**video Explanation link**
https://drive.google.com/file/d/1JJcsEahangQ8jB5eEMDrzdftJwEjS-91/view?usp=sharing


**SUMMARY**

**Problem Understanding**
In today’s digital world, finding information or products online is not hard — but navigating through endless links, filters, and irrelevant results is. Current AI assistants only give static summaries or links, leaving the user to manually search, filter, and click through websites. This gap between “knowing” and “reaching” creates frustration, wasted time, and incomplete assistance. What people truly need is not just an AI that tells them what’s available, but one that actually takes them to it.

**Proposed Prototype Solution**
Our solution is the Web Navigator AI Agent — an assistant that goes beyond advice and acts like a digital intern. The agent takes natural language instructions from the user, understands them with a locally running LLM (LangChain + Ollama), and breaks them into clear steps. Through browser automation (Playwright or Selenium), it autonomously opens websites, applies filters, searches for results, and finally lands the user directly on the exact product or page they need. The backend, built with Flask, orchestrates the process, while the frontend provides a simple input interface. Optional features like memory, retries, and voice input make the interaction smooth and human-like.

**Uniqueness and Impact**
The uniqueness of our solution lies in its direct action: unlike existing AI systems that stop at giving links or summaries, our agent takes users straight into the live webpage they need — whether it’s the cheapest flight booking page, a specific product on an e-commerce site, or the latest relevant news article. This creates a seamless bridge from intent to action, reducing effort, saving time, and transforming user experience. In essence, our project redefines AI assistance: from being just an “information provider” to becoming an action-taker that navigates the web for you.


                  **Technology Stack**
Backend & AI

Flask for coordination and control Ollama + LangChain for LLM processing Playwright for web automation SQLite for local storage

Frontend & APIs

HTML, JavaScript, Tailwind CSS Web Speech API for voice input Flask APIs for communication Text-to-Speech for confirmations


**TEAM MEMBERS AND THEIR CONTRIBUTION**

1. CHANDRIKA VULAPU – Backend Developer
2. JAGADEESH CHITTIBOINA – Automation Engineer
3. JHANSI YEJARLA – Testing & Deployment Engineer
4. MAHENDRA VARMA CHINTHARABOINA – Frontend Developer
5. BHUMIKA KESANAPALLI – AI & NLP Engineer

