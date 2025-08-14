# ProGen2 Protein Design AI

Ce dépôt contient deux notebooks démontrant l'utilisation de ProGen2 pour le design et l'analyse de protéines.

## Contenu

- **progen2_ai_generation.ipynb**  
  Pipeline minimal : génération de séquences protéiques avec ProGen2 (mirror), analyse, filtrage et visualisation 3D.

- **progen2_finetune_comparison.ipynb**  
  Pipeline complet : chargement d'un dataset public (hydrolases EC 3.*), génération baseline, fine-tuning léger avec LoRA, comparaison avant/après fine-tuning.

## Prérequis

- Python 3.10+
- [PyTorch](https://pytorch.org/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- Google Colab (Premium recommandé pour le fine-tuning)

## Installation rapide

Clonez le dépôt :
```bash
git clone https://github.com/<VOTRE_UTILISATEUR>/progen2-protein-design-ai.git
cd progen2-protein-design-ai
```
