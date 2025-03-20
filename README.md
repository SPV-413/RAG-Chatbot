# RAG Chatbot with Flowise AI, GPT-4o Mini, and Vectara
Developed a **Retrieval-Augmented Generation (RAG) chatbot** using **Flowise AI** for workflow orchestration, **GPT-4o Mini** as the generative language model, and **Vectara** for efficient vector storage and semantic search. This enhances AI-generated responses by retrieving relevant information from an uploaded PDF file. It is ideal for knowledge management, research, or customer support, it transforms static data into dynamic conversational experiences.

## Features
- **Flowise AI**: A no-code/low-code platform for building AI workflows.
- **GPT-4o Mini**: A lightweight yet efficient language model for generating responses.
- **Vectara**: A semantic search engine that retrieves relevant information from uploaded PDFs.
- **PDF-Based Retrieval**: The chatbot processes and queries the content of an uploaded PDF to provide precise answers.

## Installation & Setup
### 1. Prerequisites
- PNPM installed
- Flowise AI installed
- API keys for OpenAI (GPT-4o Mini) and Vectara

### 2. Simple setup using PNPM:
- Clone the repository: git clone https://github.com/FlowiseAI/Flowise.git
- Go into repository folder: cd Flowise
- Install all dependencies of all modules: pnpm install
- Build the code: pnpm build

### 3. Start Flowise
pnpm start

### 4. Open
http://localhost:3000

### 5. Configure API Keys
- **GPT-4o Mini API Key**
  - Sign up at OpenAI if you don't have an account.
  -  Get your API key from the OpenAI dashboard.
  -  Set the API key in Flowise AI.
- **Vectara API Key**
  - Sign up at Vectara and create a new corpus.
  -  Get the API key and set it in Flowise AI.

### 6. Upload a PDF file
Store the document in Vectara’s database for retrieval.

### 7. Start the chatbot
Designed to process user-uploaded PDF files, the system extracts text, converts it into vector embeddings via Vectara, and retrieves contextually relevant data to generate accurate, context-aware responses using GPT-4o Mini.

## Use Cases
- Organizations handling large amounts of textual data.
- Industries requiring quick document retrieval for decision-making.
- Customer service & support teams looking to automate responses.
- Academia & research fields needing efficient information retrieval.

## Contact
For any inquiries, reach out via GitHub or email.
