A multimodal LLM is an AI model that can process, understand, and generate information from different types of data, or "modalities," beyond just text. These models can handle a combination of inputs like images, audio, and video, allowing them to perform tasks that require a holistic understanding of different data types, similar to how humans perceive the world. 

Examples include GPT-4o and Gemini.

Library used PyMUODF (fitz), CLIP Model, CLIP processor

Multimodal app created used CLIP (Cibtrastive Lanbguage Image Pre-training) from OpenAI for generating vector embeddings, that are stored in FAISS

Retriever output needs to be formated before sending it to LLM along with querty for generating final output.
