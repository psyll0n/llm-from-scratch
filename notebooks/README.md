# Notebooks

Google Colab notebooks for each part of the workshop. Each notebook is self-contained: includes `!pip install` and data download cells, and works with GPU (T4) via **Runtime → Change runtime type → GPU**.

| Notebook                                                     | Contents                                                                                                                                                    |
| ------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [01-tokenization.ipynb](01-tokenization.ipynb)               | Builds the character-level tokenizer, compares it to BPE via tiktoken, visualizes bigram density and vocab size impact                                      |
| [02-the-transformer.ipynb](02-the-transformer.ipynb)         | Implements `GPTConfig`, `CausalSelfAttention`, `MLP`, `Block`, and `GPT` step-by-step with shape checks and parameter breakdowns                            |
| [03-training-loop.ipynb](03-training-loop.ipynb)             | Full training loop with data loading, cosine LR schedule (plotted), gradient clipping, checkpointing, and loss curve plotting                               |
| [04-text-generation.ipynb](04-text-generation.ipynb)         | Greedy decoding, temperature and top-k visualized as probability distributions, seed reproducibility, cherry-picking                                        |
| [05-putting-it-together.ipynb](05-putting-it-together.ipynb) | All-in-one notebook — train on Shakespeare, plot overfitting curves, run experiments on model size / context length / LR                                    |
| [06-competition.ipynb](06-competition.ipynb)                 | Competition setup with dropout added to the model, data download options, BPE tokenizer support, best-checkpoint saving, and a reproducible submission cell |
