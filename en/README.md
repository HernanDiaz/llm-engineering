<div align="center">
  <h1>Building Applications with Language Models</h1>
  <h3><em>Prompts, RAG, tools and evaluation with open LLMs in Python</em></h3>
  <p><img src="portada.png" alt="Book cover" width="280"></p>
  <p>by <strong>Hernán Díaz Rodríguez, PhD</strong> · Professor at the University of Oviedo</p>
  <p>
    <a href="https://creativecommons.org/licenses/by-nc/4.0/"><img src="https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg" alt="License: CC BY-NC 4.0"></a>
    <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python">
    <img src="https://img.shields.io/badge/Colab-free%20T4%20GPU-orange?logo=googlecolab" alt="Colab">
  </p>
  <p>
    <a href="https://www.amazon.com/dp/B0HMX9N1KQ"><img src="https://img.shields.io/badge/Amazon-Paperback-FF9900?logo=amazon&logoColor=white" alt="Paperback on Amazon"></a>
    <a href="https://www.amazon.com/dp/B0HMX44VJ4"><img src="https://img.shields.io/badge/Amazon-Kindle-FF9900?logo=amazon&logoColor=white" alt="Kindle on Amazon"></a>
  </p>
</div>

---

## The book

**Building Applications with Language Models** teaches how to build reliable applications on top of an already trained language model. Over twelve chapters, it builds, piece by piece, the customer service assistant of **North Cycles**, a bicycle store in Portland, Oregon: prompts that work, examples and reasoning, structured outputs, semantic search, RAG, context and cost management, function calling, LoRA fine-tuning, evaluation and guardrails. The last chapter puts all the pieces together into an application with a web interface.

Everything runs on **free, open models**, with no API keys or paid services: Qwen2.5-1.5B-Instruct on Colab's free GPU and, without a GPU, Qwen3-0.6B on the processor. Every figure in the book comes from an experiment you can repeat in the chapter's notebook. This edition is not a plain translation: the store, its data and every experiment are its own, run in English.

It belongs to the **AI in Practice** series: hands-on books on artificial intelligence, with original experiments, a notebook and a video in every chapter.

> *¿Prefieres español?* La edición española, **Ingeniería de aplicaciones con modelos de lenguaje**, está en la [raíz del repositorio](../).

---

## Chapters

Each chapter has its notebook on Google Colab and its video, with Robotín and the author. All the videos are in the [YouTube playlist](https://www.youtube.com/playlist?list=PLVNs0ZclLRpU).

| Ch. | Title | Notebook | Video |
|-----|-------|----------|-------|
| 1 | Prompts that work | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/01_Prompts_that_work.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=VV9YdRJBI-Y&list=PLVNs0ZclLRpU) |
| 2 | Examples and step-by-step reasoning | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/02_Examples_and_reasoning.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=AGU0GM7Puqw&list=PLVNs0ZclLRpU) |
| 3 | Structured outputs | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/03_Structured_outputs.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=ywFXhDJA32A&list=PLVNs0ZclLRpU) |
| 4 | Embeddings and semantic search | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/04_Embeddings_and_semantic_search.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=ksyWlUJ9PV4&list=PLVNs0ZclLRpU) |
| 5 | Retrieval-augmented generation (RAG) | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/05_RAG.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=BmyCZPz30Ik&list=PLVNs0ZclLRpU) |
| 6 | Advanced RAG | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/06_Advanced_RAG.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=L-lZmL8JjvU&list=PLVNs0ZclLRpU) |
| 7 | Managing context and cost | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/07_Managing_context_and_cost.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=VDT-m7dPXoI&list=PLVNs0ZclLRpU) |
| 8 | Function calling | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/08_Function_calling.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=NjONnk-5Fps&list=PLVNs0ZclLRpU) |
| 9 | Fine-tuning with LoRA | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/09_Fine_tuning_with_LoRA.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=Bx0_qAPuSDo&list=PLVNs0ZclLRpU) |
| 10 | Evaluating an LLM application | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/10_Evaluation.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=4X3_vVUPzE4&list=PLVNs0ZclLRpU) |
| 11 | Guardrails | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/11_Guardrails.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=UiXjYAaxmc0&list=PLVNs0ZclLRpU) |
| 12 | Project: the North Cycles assistant | [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HernanDiaz/llm-engineering/blob/main/en/notebooks/12_Complete_assistant.ipynb) | [![Watch on YouTube](https://img.shields.io/badge/YouTube-Watch-red?logo=youtube)](https://www.youtube.com/watch?v=HHkUzIg5p48&list=PLVNs0ZclLRpU) |

---

## How to use the notebooks

- Click **Open in Colab** and run the cells in order. Nothing needs to be installed.
- Turn on the free GPU: *Runtime → Change runtime type → T4 GPU*. Without a GPU, the notebooks choose a smaller model that runs on the processor, more slowly.
- The notebooks download the files of the `data/` folder by themselves the first time.

## Data

North Cycles and all its data are fictional: e-mails, FAQ, terms and conditions, catalog, orders, stock and the test sets of each chapter, in [`data/`](./data). The manual labels used in chapter 10 are in [`chapter_10/`](./chapter_10).

---

## License

This material is distributed under the [Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/) license: it can be used and adapted for teaching and study, crediting the author, but not for commercial purposes. The models used by the notebooks have their own licenses: Qwen2.5 and Qwen3 (Apache 2.0), multilingual-e5-base (MIT) and bge-reranker-v2-m3 (Apache 2.0).
