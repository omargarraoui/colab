# AI Problem Solver 🧠🤖

Modello di intelligenza artificiale fine-tunato per il problem solving complesso, basato su [Llama 3.2 3B](https://huggingface.co/unsloth/Llama-3.2-3B-Instruct) e ottimizzato con la libreria [Unsloth](https://github.com/unslothai/unsloth).

## 📌 Caratteristiche principali

- 🔬 **Fine-tuning** su dataset UltraInteract (`openbmb/UltraInteract_sft`)
- 💾 **Quantizzazione a 4-bit** per ridotto impatto in memoria
- 🧩 **Supporto per sequenze lunghe** (fino a 4096 token)
- 🔁 **Template personalizzati** per addestramento e inferenza
- ⚙️ **Esportazione in formato GGUF** compatibile con `llama.cpp`
- 🧠 Ottimizzato per compiti di ragionamento e problem solving strutturato

## 🚀 Requisiti

- GPU con supporto FP16 o BF16 (es. T4, A100, V100)
- Python 3.10+
- PyTorch, Transformers, Datasets, Unsloth, TRL

## 📦 Installazione

```bash
pip install unsloth
pip uninstall unsloth -y && pip install --upgrade --no-cache-dir --no-deps git+https://github.com/unslothai/unsloth.git
