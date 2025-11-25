---
task_categories:
- text-classification
language:
- ne
size_categories:
- n<1K
pretty_name: Ecommerce intent classification in Roman Nepali
dataset_info:
  features:
  - name: id
    dtype: int64
  - name: question
    dtype: string
  - name: answer
    dtype: string
  - name: intent
    dtype: string
  - name: text
    dtype: string
  - name: label
    dtype: string
  splits:
  - name: train
    num_bytes: 270854
    num_examples: 1500
  download_size: 38752
  dataset_size: 270854
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
---
# Roman Nepali Ecommerce Intent

## Dataset Details
This is a sample dataset just to learn about dataset so this is a small dataset of Ecommerce intent classification in Roman Nepali language.