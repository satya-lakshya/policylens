# PolicyLens

Ask questions in plain language and get answers from policy documents, with the source passages cited.

- Retrieval-augmented generation: documents are split into chunks, embedded, and searched with FAISS
- The model answers only from the retrieved text and shows which policy passages it used
- Backend: FastAPI, with OpenAI or Gemini and a fallback between them. Frontend: Next.js and Tailwind
- A student project. No raw data or secrets are stored in the repo

Formerly named Policy_Assistant.
