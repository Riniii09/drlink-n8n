# Dr. Link 🥼 AI-Powered Doctor Finder
**3rd Place — AI Agents Hackathon, Swafinix Technologies [(Unstop)](https://unstop.com/hackathons/ai-agents-hackathon-swafinix-technologies-pvt-ltd-1529586)**  

<img width="956" height="409" alt="image" src="https://github.com/user-attachments/assets/0371a257-31a9-4e80-b56b-ebdc49060236" />  

---

## Problem Statement  
Finding a doctor quickly, especially one who is both verified and available can be stressful. Traditional search methods require manual browsing, adding filters, sorting, calling and waiting.  

---

## Automation Module  
This module forms the **automation backbone** of **Dr. Link**, enabling users to search for doctors using **natural language queries** and instantly get relevant matches from a **verified database**.  

---

### Key Features (Hackathon Build)
- **Natural Language Search** — Users can type queries like:  
  > “I have a heartburn, which doctor is available right now?”  
- **Vector Database Search** — Doctor profiles stored in **Pinecone** for semantic matching.  
- **End-to-End Automation** — All steps handled within **n8n** workflows.  
- **Booking Prototype** — Saves booking info to a document (dynamic calendar integration coming soon).  

---

## How It Works  
1. **User Query** — User submits a request via chat.  
2. **n8n Workflow Trigger** — Captures the query.  
3. **Pinecone Vector Search** — Finds the closest matching doctors from the verified database.  
4. **Result Formatting** — n8n prepares the result for display.  
5. **Booking Step** — Adds booking details to a doc file for now.  

---

## Dr. Link — The Bigger Picture  
Outside the hackathon module, Dr. Link also includes:  
- **📞 AI Calling Agent** — Calls doctor offices to schedule appointments, [check it out here!](https://github.com/Pavithranpillai08/Dr.Link-AI-Calling-agent)
- **🎨 Frontend UI** — Sleek, modern clutter-free interface.  

---

## 🧑‍💻 Tech Stack (Automation Module)  
- **Platform:** n8n  
- **Database:** Pinecone (Vector DB)  
- **AI Model:** Google Gemini
- **Automation:** Custom n8n workflows  

---

## 🙌 Team  
- **Rini Pillai** — Automation & n8n integration  
- **Pavithran Pillai** — AI calling agent  
- **Krishnapriya Padmajan** — Frontend design
  
---

## [Check out the all demo videos here!](https://drive.google.com/drive/folders/1YELVnrXfAvWK2PdA8yCSaQ8jbw7vgyvZ?usp=sharing)
