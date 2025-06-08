# Fine-Tuning and Evaluating LLaMA2-7B
This project demonstrates the process of **fine-tuning a LLaMA2-7B language model** and evaluating its performance using multiple datasets. The entire workflow is implemented in Jupyter Notebooks for transparency and reproducibility.

## 🔧 Project Overview
- **Model:** LLaMA2-7B

- **Fine-tuning:** Performed using the CulturaX Lithuanina dataset.

- **Evaluation:** Perplexity evaluated using the neurotechnology Lithuanian-qa-v1 dataset. The accuracy of the MMLU dataset evaluated using the neurotechnology translated MMLU dataset.

- **Environment:** Jupyter Notebook (.ipynb)

## 📁 Project Structure
- **training/** - the training file

- **perplexityEvaluation/** - perplexity evaluation files

- **MMLUEvaluation/** - accuracy evalluation for the MMLU dataset

## 📌 Features
- Efficient 4-bit quantized fine-tuning

- Use of QLoRA/PEFT for memory-efficient adaptation.

- Dataset preprocessing and formatting.

- Evaluation across multiple benchmarks.

## 📊 Datasets Used
- **[CulturaX](https://huggingface.co/datasets/uonlp/CulturaX/viewer/lt)** - Fine-tuning

- **[neurotechnology lt_mmlu](https://huggingface.co/datasets/neurotechnology/lt_mmlu/viewer/all/validation)** - MMLU dataset accuracy evaluation

- **[neurotechnology lithuanian-qa-v1](https://huggingface.co/datasets/neurotechnology/lithuanian-qa-v1)** - perplexity evaluation

## 🧪 Results
You can present results here in a table:

**MMLU accuracy:**
| model | accuracy |
| ------- | -------- |
| Llama2-7b | 24.78% |
| Lt-Llama2-7b | 24.67% |
| fine-tuned Llama2-7b | 25.17% |

\
\
**perplexity:** (lower is better)
| model | perplexity |
| ------- | -------- |
| Llama2-7b | 15.98 |
| Lt-Llama2-7b | 3.85 |
| fine-tuned Llama2-7b | 7.85 |


## 🛠 Tools & Libraries
- Transformers (Hugging Face)

- PEFT / LoRA

- Datasets

- JupyterLab / Notebook

## 🙋‍♀️ Acknowledgements
Meta AI for LLaMA2

Hugging Face ecosystem

Neurotechnology

