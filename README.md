# RAG-FAQs

Built a Retrieval-Augmented Generation (RAG) system using n8n, and it’s fully automated from document ingestion to AI chat responses.

Workflow overview 👇

 📥 Download document (Google Drive)
 
 📄 Extract content from PDF
 
 ✂️ Split text into chunks
 
 🧠 Generate embeddings using Hugging Face
 
 📦 Store & retrieve vectors with Pinecone
 
 ⚡ Chat powered by Groq (LLaMA 3)
 
 💬 AI Agent answers questions only from the uploaded data
 
This setup allows users to chat with their own documents while keeping responses accurate and grounded in real data.
Perfect for:

 ✔️ FAQs
 
 ✔️ Knowledge bases
 
 ✔️ Internal docs
 
 ✔️ Support chatbots
 
Built completely inside n8n with no heavy backend code.

If you’re exploring RAG, n8n automation, or AI workflows, this approach is super powerful.

<img width="1121" height="439" alt="image" src="https://github.com/user-attachments/assets/2ed960b2-a11f-4dfb-b4a9-abeae9181eb9" />
