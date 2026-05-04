---
license: apache-2.0
dataset_info:
  features:
  - name: Entry
    dtype: string
  - name: Label
    dtype: string
  - name: Sequence
    dtype: string
  splits:
  - name: train
    num_bytes: 290485
    num_examples: 512
  - name: test
    num_bytes: 85231
    num_examples: 128
  download_size: 372319
  dataset_size: 375716
configs:
- config_name: default
  data_files:
  - split: train
    path: data/train-*
  - split: test
    path: data/test-*
---
