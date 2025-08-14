# ProGen2 Protein Design AI

This repository contains two Jupyter notebooks demonstrating the use of **ProGen2** for AI-assisted protein generation and analysis.

## Contents

- **`progen2_ai_generation.ipynb`**  
  Generates novel protein sequences with **ProGen2 (mirror)**, applies filtering based on biochemical properties, and predicts 3D structures with **ESMFold**.

- **`progen2_finetune_comparison.ipynb`**  
  Loads a public dataset of hydrolases (EC 3.*), performs **LoRA fine-tuning** on ProGen2, and compares generation results **before and after fine-tuning**.

## Requirements

- Python 3.10+  
- Google Colab (Premium recommended for faster execution)  
- Packages: `transformers`, `tokenizers`, `pandas`, `numpy`, `matplotlib`, `py3Dmol`, `requests`

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/<your-username>/progen2-protein-design-ai.git
   cd progen2-protein-design-ai
   ```

2. Open one of the notebooks in Google Colab.

3. Follow the execution blocks in order.  

   - The **generation notebook** shows basic protein design.  
   - The **fine-tuning notebook** demonstrates dataset-based adaptation and performance comparison.

## Notes

- All generated proteins are **in silico predictions** and **must be validated experimentally** before any use.
- The dataset used for fine-tuning comes from **UniProt (Hydrolases, EC 3.*)**.
