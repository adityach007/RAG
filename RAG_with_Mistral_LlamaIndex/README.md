# RAG with Mistral and LlamaIndex

## Uses of the imports and libraries:

**1. llama-index-llms-huggingface**: Since we are not using hugging face models from the huggingface hub. So, this integration package allows us to use huggingface hosted models.

**2. llama-index**: This the data framework which we will be using for RAG.

**3. VectorStoreIndex**: This is used to built the indexes of the documents.

**4. SimpleDirectoryReader**: This is used to read the documents from the directory (in our case the directory is /content/name.pdf).

**5. HuggingFaceLLM**: For the initialization of the LLM models of the huggingface.

**6. PromptTemplate**: For defining the prompt structure to be used (in our case it is <|USER|>{query_str}<|ASSISTANT|>, this is the default prompt structure in many cases).

**7. llama-index-embeddings-huggingface and llama-index-embeddings-instructor**: These are support tools to llamaindex and hence we will be able to use the huggingface and llamaindex embeddings for converting the documents into corresponding vectors.

**8. HuggingFaceEmbedding**: We have utitlized huggingface embeddings by using the sentence transformer model.

**9. Settings**:
