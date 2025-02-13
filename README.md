# Technical Test for Internship Program 2025  
Please follow the instructions below to complete the test.  

### **Task Overview**  
Develop a **Generative AI Chatbot** that integrates with **LINE** and utilizes **Google Gemini API** for response generation. Implement **Retrieval-Augmented Generation (RAG)** to enhance responses based on uploaded text documents.

<p align="left">
  <img src="diagram.png" width="640"/>
</p>

### **Instructions**  
1. **Develop the chatbot backend using FastAPI**  
2. **Connect the chatbot to LINE Messaging API** for real-time conversations
3. **Use Google Gemini API for response generation**  
4. **Implement Retrieval-Augmented Generation (RAG):**  
   - Retrieve relevant snippets from uploaded text files  
   - Use in-memory search (TF-IDF, BM25, or simple embedding-based retrieval) 
5. **Create a backend API to upload and manage text documents (.txt only)**  
   - Provide endpoint to upload new text files for RAG 
   - Store files in memory or temporary storage (no database)
   - Provide endpoints to GET and PUT prompt data
6. **Deploy the chatbot to cloud service**  
7. **Push the completed project to your public GitHub repository** and provide the link in the answer box  

### **Extra score** 
1. Using Mongo database to keep chatlog
2. Implement Chat history

### Evaluation Criteria 
1. **Code Quality** – Well-structured, maintainable, and documented
2. **Correct response** – Bot answer with correct information
3. **User Experience** – The chatbot provides clear and structured responses