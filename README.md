# Synthetic Mixed-Language Emotion (SMiLE) Analysis Data 

This repository serves as a resource for our unpublished paper, containing synthetic data for sentiment analysis in Spanglish and Malayalam-English code-mixed texts.

## Contents
The repository consists of two main folders:

### Spanglish
- **ensp_scm_[5k,10k,15k,25k,50k].pkl:** Synthetic Data Size (perfect data size)
- **ensp_scm_[15ex, 50ex, 150ex, 500ex].pkl:** Shot Size (raw data size)
- **ensp_scm_[150exsmall, 150ex08].pkl:** Temperature (raw data size)

### Malayalam-English
- **enma_scm_all.pkl:** All generated data (raw)
- **enma_scm_15k_150ex.pkl:** Synthetic data used for training

All files are pickle files containing dictionaries with the following structure:
```python
{
    random_number_1: ['sentence', 'sentiment'],
    random_number_2: ['sentence', 'sentiment'],
    ...
}
