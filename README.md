Medical Chat Bot    

Developed a  open-source LLM applications on CPUs using LLama 2, C Transformers, GGML, and LangChain

In this project, we will discover how to run quantized versions of open-source LLMs on local CPU inference for document question-and-answer (Q&A). 

Download LLM model file & save in project folder.

https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/blob/main/llama-2-7b-chat.ggmlv3.q8_0.bin


Data folder Contain local knowledge for QA in pdf format

Run ingest.py to vectorsize the text and store in faiss DB

Run Chainlit using chainlit run model.py -w
