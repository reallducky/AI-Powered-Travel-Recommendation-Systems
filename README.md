Project Overview:

  -  Implements a hotel review recommender system using NLP techniques (Sentence-BERT, prompt engineering, and LLMs).
  -  Compares two large language models (OpenAI's ChatGPT and Llama) for text summarization and recommendation.
Key Techniques:

  -  Sentence-BERT (SBERT): Used for generating sentence embeddings to retrieve semantically similar hotel reviews.
  -  Prompt Engineering: Designed to provide context to the LLM, ensuring relevant and accurate summaries.
  -  Large Language Models (LLMs): ChatGPT and Llama generate concise and insightful summaries based on hotel reviews.
Datasets:

  -  Vienna Dataset: 20,301 reviews.
  -  Aspen Dataset: 2,006 reviews.
  -  Both datasets include star ratings, hotel names, review titles, and review texts. Data is provided by the GitHub repository here.
Experiment Setup:

  -  Document Embedding: BERT tokenization and SBERT embeddings used for text analysis and review retrieval.
  -  Prompt Creation: Reviews are combined into a “super prompt” for summarization.
  -  LLM Summarization: The super prompt is processed by both ChatGPT and Llama for response generation.
Results:

  -  Aspen Dataset (Small): Both models provide accurate summaries, with ChatGPT generating more detailed responses.
  -  Vienna Dataset (Large): ChatGPT outperforms Llama in generating detailed, adjective-rich summaries.
Evaluation:

  -  ChatGPT produces more nuanced responses with a larger dataset.
  -  Limma (smaller model) provides concise responses and is more cost-effective.
Future Work:

  -  Exploring other LLMs for summarization.
  -  Updating datasets to improve the recommender system's accuracy and timeliness.
  -  Installation Instructions:

Clone the repository and install dependencies:

-  git clone https://github.com/youngjeong46/travel-recommender.git
-  cd travel-recommender
-  pip install -r requirements.txt

License:

-  MIT License.


Acknowledgments
-  Reimers, N., & Gurevych, I. (2019). Sentence-BERT: Sentence Embeddings using Siamese BERT Networks.

-  Gao, Y., et al. (2024). Retrieval-augmented generation for large language models: A survey.


References
  -  Reimers, N., & Gurevych, I. (2019). Sentence-BERT: Sentence embeddings using Siamese BERT-Networks. Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing and the 9th International Joint Conference on Natural Language Processing (EMNLP-IJCNLP). DOI
  -  Gao, Y., Xiong, Y., Gao, X., Jia, K., Pan, J., Bi, Y., Dai, Y., Sun, J., Wang, M., & Wang, H. (2024, March 27). Retrieval-augmented generation for large language models: A survey. arXiv. arXiv link
