# Data and code to support the paper [**A Compositional Calculus for Semantic Synergy in Language Model Embeddings**](https://openreview.net/pdf?id=bGMPERlw5f)
A paper at the ICML2026 *Mechanistic Interpretability* workshop, and the workshop on *Compositional Learning: Safety, Interpretability, and Agents*.

- `basic_results_reproduction` is a jupyter notebook with code to reproduce the central calculations and figures. It loads the `Qwen3-Embedding-0.6B` model, and then should take under 10 seconds to run on a laptop.
- `data/idiom_literal_pairs.csv` contains the 107 paired idioms and literals with their meanings. 
- `data/idiom_literal_pairs_extended.csv` contains the LLM-extended list of 836 pairs. 
- `data/names.csv` contains the names used in the compositional vs non-compositional name analysis. 
