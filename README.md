# 🍏 GraphRAG: KG-Enhanced LLM
This repository contains my investigations of recent research papers related to Graph RAG, conducted during July to August 2024.

- Initially, I practiced the basic implementations of deep learning by following the *Dive into Deep Learning* book ([link](https://github.com/ohmyksh/d2l-practice)).  
- Following that, I surveyed major and recent papers in the area of graph RAG, which I am particularly interested in, and selected a few for deeper analysis.

### 🤔 Knowledge Graph + LLM? 
GraphRAG is an enhancement of the widely-used RAG (Retrieval-Augmented Generation) approach. It incorporates a graph database as a source of contextual information that is fed into the Large Language Model (LLM). This method leverages the structured and factual nature of knowledge graphs, using them either as a reasoning source or as a database for retrieval. Graph RAG further improves the accuracy, reliability, and traceability of the model’s reasoning process by incorporating graph databases as sources of contextual information.  

🌱 I am interested in research that utilizes knowledge graphs to enhance the reasoning capabilities and accuracy of LLMs, with a particular focus on exploring solutions to advance this field.

  
The investigation process was as follows:
1. **In-depth Paper Review:** I thoroughly read and summarized the papers at the implementation level to identify the key components to implement. Also, I presented the paper using the following slides.  
2. **Pseudocode Development:** Based on the papers, I created detailed pseudocode.
3. **Implementation (selectively):** I then proceeded with the implementation based on the developed pseudocode.
- Due to resource constraints (time and cost), I was unable to fully replicate the results of the paper. However, I have documented the process during the implementation process.
  
  
| Model                          | 📄 Paper                                                                                                           | 📊 Slide                                                                                                     | 📝 Pseudocode      | 💻 Implementation    |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|-------------------|----------------------|
| ToG (ICLR 2024)                 | [Think-on-Graph: Deep and Responsible Reasoning of Large Language Model on Knowledge Graph](https://arxiv.org/pdf/2307.07697) | -                                                                                                             | [Docs](https://docs.google.com/document/d/1nlVzzWdPAFoy024avGfwifywatzZfQMVWhBAK0o9Ppw/edit?usp=sharing)         | [Repo](https://github.com/ohmyksh/ToG/blob/main/README.md) |
| G-Retriever (Arxiv 2024)        | [G-Retriever: Retrieval-Augmented Generation for Textual Graph Understanding and Question Answering](https://arxiv.org/pdf/2402.07630) | [Slides](https://docs.google.com/presentation/d/13x4nCIEbD_zkHYLA8MwRljcDAo4e9OW0nDlmfqNwyFU/edit?usp=sharing) | [Docs](https://docs.google.com/document/d/15IPYGIG0KC5-jS74E1aRlGbTtztfOO9hM_Xn6Gnf220/edit?usp=sharing)     | [Repo](https://github.com/ohmyksh/G-Retriever/tree/master)                 |
| RoG (ICLR 2024)                 | [Reasoning on Graphs: Faithful and Interpretable Large Language Model Reasoning](https://arxiv.org/pdf/2310.01061) | [Slides](https://docs.google.com/presentation/d/1pB4jLnPFqqGTd-EXhuAIZkPpdj9hb1Wz50TqYYPVrZY/edit?usp=sharing) | [Docs](https://docs.google.com/document/d/1VF_Hn_Ciff6Kcglpv4dX6yLUf8u5ZRWETnYSIigJqiY/edit?usp=sharing)        | -      |
| From Local to Global (Arxiv 2024)| [From Local to Global: A Graph RAG Approach to Query-Focused Summarization](https://arxiv.org/pdf/2404.16130)     | [Slides](https://docs.google.com/presentation/d/1nwQGz8d2yiAxc5uu9EWz357QLL8-AO6qxjZYjaZzD9c/edit?usp=sharing) | -     | -      |
