# Implementing Gemini AI

## 📌 Objective

Understand how to integrate Gemini AI Models to power chatbot responses 

---

## 📘 Workflow

Workflow Understand 
- how to integrate Gemini AI models to power chatbot responsesIn our hands-on project,
- we implemented this flow using a Vanilla JavaScript frontend and a Node.js + Express backend. When the user submits a message through the chat form, the frontend sends a POST request to the /api/chat endpoint on the backend.
- The backend then uses the Gemini SDK’s generateContent() method to prompt the AI model with the user’s message.
-  Once Gemini returns the response, it’s sent back to the frontend and displayed in the chat interface.This architecture allows us to keep the AI logic on the backend—ensuring security and scalability—while delivering a seamless conversational experience to the user.

---


