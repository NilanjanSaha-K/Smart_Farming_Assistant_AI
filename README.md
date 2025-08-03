# AgroGuide – AI Farming Assistant

AgroGuide is an AI-powered assistant designed to support small-scale farmers, home gardeners, and spiritual plant growers by delivering real-time, hyperlocal agricultural advice in simple language. Built entirely on IBM Cloud using Retrieval-Augmented Generation (RAG), IBM Watson, and no-code tools, AgroGuide makes expert farming support accessible to all — without the need for digital literacy.

---

## Problem Statement

Farmers in India often face delayed access to expert guidance due to fragmented data, language barriers, and technical limitations. AgroGuide bridges this gap by offering a unified, multilingual AI assistant capable of answering crop, weather, and pest-related queries in real time.

---

## Features

- RAG-based AI agent using IBM Watsonx and Granite models  
- Real-time data from AgMarknet, IMD, and ICAR APIs  
- Multilingual chat interface (supports Hindi & English)  
- Crop recommendations, pest solutions, and mandi prices  
- Proactive alerts for weather or sowing risks  
- Plant image recognition (for gardening use cases)  
- No-code deployment optimized for mobile use

---

## Tech Stack

| Component              | Technology Used                       |
|------------------------|----------------------------------------|
| Backend                | IBM Cloud Functions, Flask (Optional)  |
| AI/ML                  | Watsonx AI Studio, IBM Granite (RAG)   |
| NLP                    | IBM Watson Assistant / NLU             |
| External APIs          | AgMarknet, IMD Weather, ICAR Crop DB   |
| Image Processing       | TensorFlow / IBM Watson ML             |
| Deployment             | IBM Cloud (No-code / Cloud Foundry)    |
| Frontend               | React.js / HTML + Bootstrap            |

---

## How It Works

1. User sends a text/image query via chat interface  
2. Query is classified and routed to either RAG/Watson or ML model  
3. Real-time external data is fetched if needed  
4. Agent composes and returns a personalized, actionable response  
5. Logs and feedback are stored for improvement

---

## Getting Started

### Prerequisites
- IBM Cloud account (Lite Tier)
- Watson Assistant or Watsonx AI Studio access
- AgMarknet + IMD API keys (free or developer access)
