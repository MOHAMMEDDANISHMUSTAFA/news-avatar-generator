# AI News Avatar Generator

An end‑to‑end AI pipeline that automatically scrapes real‑time news, summarizes it using LLMs, generates a natural news‑presenter script, and produces a talking‑avatar video using D‑ID. Built with FastAPI, OpenAI, and automated orchestration.

---

## 🚀 Project Overview

This system automates the entire workflow of creating short AI‑generated news videos:

1. **Scrapes live news** from trusted sources  
2. **Summarizes content** using AI  
3. **Generates a presenter‑style script**  
4. **Creates a talking‑avatar video** using D‑ID  
5. **Serves everything through a FastAPI backend**

The result is a fully automated AI news‑generation pipeline designed for speed, efficiency, and real‑world usability.

---

## 🎥 Demo Video

👉 Watch the demo here:  
**Google Drive- (https://drive.google.com/drive/folders/1r6E06vWPUXAX4uOHVhg9NxQip383MXhv?usp=drive_link)**

---

## 🧠 Features

- Automated news scraping  
- AI‑powered summarization  
- Natural script generation  
- Avatar video creation (D‑ID API)  
- FastAPI backend with clean endpoints  
- Local video storage + download API  
- Fully modular and production‑ready architecture  

---

## 🧩 Models Used & Cost Breakdown

This project is optimized for **low cost** and **fast generation**.  
Below is the exact breakdown of the models used and how much each step costs.

### 🔹 **1. Summarization Model**
**Model:** `gpt-4o-mini`  
**Usage:** Summarizes scraped news into a clean, short paragraph  
**Cost:** ~$0.001–$0.003 per summary  
**Latency:** ~1–2 seconds  

---

### 🔹 **2. Script Generation Model**
**Model:** `gpt-4o-mini`  
**Usage:** Converts the summary into a natural news‑presenter script  
**Cost:** ~$0.001–$0.003 per script  
**Latency:** ~1–2 seconds  

---

### 🔹 **3. Avatar Video Generation**
**Service:** D‑ID API  
**Usage:** Generates a talking‑avatar video using the script + audio  
**Cost:** ~$0.05–$0.10 per 15 seconds  
**Latency:** ~8–15 seconds  

---

## ⏱️ Performance Summary

| Step | Time |
|------|------|
| News scraping | 0.5–1 sec |
| AI summarization | 1–2 sec |
| Script generation | 1–2 sec |
| Audio generation | 2–4 sec |
| Avatar video generation | 8–15 sec |
| **Total end‑to‑end time** | **12–25 seconds** |

---

## 💰 Total Cost Per Video

| Component | Cost |
|----------|------|
| OpenAI summarization | ~$0.001–$0.003 |
| Script generation | ~$0.001–$0.003 |
| D‑ID video generation | ~$0.05–$0.10 |
| **Total cost per video** | **~$0.06–$0.12** |

This makes the system extremely affordable for automated daily news content.

---

## 🛠 Tech Stack

- **Python**
- **FastAPI**
- **OpenAI API**
- **D‑ID API**
- **HTTPX / Requests**
- **Feedparser**
- **BeautifulSoup4**
- **Uvicorn**

---

## 📌 Why This Project Matters

This project demonstrates:

- End‑to‑end AI engineering  
- API integration and orchestration  
- Backend development  
- Automation of real‑world AI workflows  
- Clean, modular system design  
- Cost‑aware and latency‑optimized architecture  

Perfect for showcasing practical AI engineering skills to recruiters.

---

## 🔒 Note

This repository contains **documentation and demo output only**.  
The full source code is kept private for security and API‑key protection.
