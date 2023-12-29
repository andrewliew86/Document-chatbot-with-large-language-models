# Q&A chatbot with RAG on PDFs and websites using LangChain, LlamaIndex and Mistral
Background:
Although commercially-available large language models (LLMs) are very powerful, there are often concerns about data privacy when utilizing these models. In this proof of concept study, I utilized open access libraries (Llama Index, LangChain, HuggingFace) to construct a chatbot that can generate answers from an uploaded PDF or webpage (retrieval augmented generation [RAG]). 

Results:
I did some preliminary testing with Mistra-7b LLM and found decent performance with answering questions from a scientific paper. Testing with PDFs/websites from other domains is ongoing.

Python libraries/tools: Llama Index, LangChain, 🤗 transformers, PyTorch. 
