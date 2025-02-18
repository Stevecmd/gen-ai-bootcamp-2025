# language-learning-assistant
A progressive learning tool that demonstrates how RAG and agents can enhance language learning by grounding responses in real Kiswahili lesson content. The system shows the evolution from basic LLM responses to a fully contextual learning assistant, This is an exploration into technical implementation and practical benefits of RAG.

**Technical Uncertainty:**
1. How effectively can we process and structure bilingual (Swahili/English) content for RAG?
2. What's the optimal way to chunk and embed Japanese language content?
3. How can we effectively demonstrate the progression from base LLM to RAG to students?
4. Can we maintain context accuracy when retrieving Swahili language examples?
5. What's the most effective way to structure multiple-choice questions from retrieved content?

**Technical Restrictions:**
* May use Amazon Bedrock for:
   * API (converse, guardrails, embeddings, agents) (https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
     * Amazon Nova Micro for text generation (https://aws.amazon.com/ai/generative-ai/nova)
   * Titan for embeddings
* Must implement in Streamlit, pandas (data visualization).
* Must use SQLite for vector storage.
* Must handle YouTube transcripts as knowledge source (YouTubeTranscriptApi: https://pypi.org/project/youtube-transcript-api/).
* Must demonstrate clear progression through stages:
   * Base LLM
   * Raw transcript
   * Structured data
   * RAG implementation
   * Interactive features
* Must include proper error handling for Swahili text processing.
* Must provide clear visualization of RAG process.
* Should work within free tier limits where possible.

## Knowledgebase

[Chroma](https://github.com/chroma-core/chroma) - Chroma is the open-source AI application database. <br/>
Embeddings, vector search, document storage, full-text search, metadata filtering, and multi-modal. <br/>
All in one place. Retrieval that just works.
