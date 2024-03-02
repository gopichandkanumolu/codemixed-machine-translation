---
language:
- en
- te
license: apache-2.0
tags:
- generated_from_trainer
metrics:
- bleu
model-index:
- name: cmt_mt5_output
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# cmt_mt5_output

This model is a fine-tuned version of [google/mt5-small](https://huggingface.co/google/mt5-small) on an unknown dataset.
It achieves the following results on the evaluation set:
- Loss: 1.8138
- Bleu: 20.3431
- Gen Len: 50.7637

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 6
- eval_batch_size: 6
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 25.0

### Training results

| Training Loss | Epoch | Step  | Validation Loss | Bleu   | Gen Len |
|:-------------:|:-----:|:-----:|:---------------:|:------:|:-------:|
| 5.9169        | 1.0   | 2167  | 3.5104          | 0.5199 | 17.752  |
| 3.9922        | 2.0   | 4334  | 3.0599          | 0.8935 | 17.9957 |
| 3.6276        | 3.0   | 6501  | 2.7670          | 1.1471 | 18.2098 |
| 3.3668        | 4.0   | 8668  | 2.5647          | 1.5464 | 18.2585 |
| 3.1707        | 5.0   | 10835 | 2.4202          | 1.9547 | 18.2031 |
| 3.0171        | 6.0   | 13002 | 2.3112          | 2.3135 | 18.2942 |
| 2.8989        | 7.0   | 15169 | 2.2182          | 2.4585 | 18.2991 |
| 2.7807        | 8.0   | 17336 | 2.1514          | 2.6652 | 18.2609 |
| 2.7062        | 9.0   | 19503 | 2.0989          | 2.8354 | 18.3249 |
| 2.6264        | 10.0  | 21670 | 2.0479          | 2.9811 | 18.2818 |
| 2.5611        | 11.0  | 23837 | 2.0080          | 3.0794 | 18.2868 |
| 2.5052        | 12.0  | 26004 | 1.9755          | 3.1549 | 18.2898 |
| 2.4635        | 13.0  | 28171 | 1.9474          | 3.2718 | 18.2911 |
| 2.4112        | 14.0  | 30338 | 1.9199          | 3.4409 | 18.2942 |
| 2.3776        | 15.0  | 32505 | 1.9013          | 3.5117 | 18.3126 |
| 2.3534        | 16.0  | 34672 | 1.8831          | 3.5478 | 18.3163 |
| 2.3213        | 17.0  | 36839 | 1.8684          | 3.5972 | 18.2615 |
| 2.2948        | 18.0  | 39006 | 1.8551          | 3.6299 | 18.296  |
| 2.2764        | 19.0  | 41173 | 1.8432          | 3.7399 | 18.2825 |
| 2.2586        | 20.0  | 43340 | 1.8332          | 3.7355 | 18.28   |
| 2.24          | 21.0  | 45507 | 1.8273          | 3.8421 | 18.2825 |
| 2.2277        | 22.0  | 47674 | 1.8217          | 3.8085 | 18.2738 |
| 2.2214        | 23.0  | 49841 | 1.8174          | 3.8219 | 18.2874 |
| 2.212         | 24.0  | 52008 | 1.8144          | 3.8045 | 18.2818 |
| 2.2088        | 25.0  | 54175 | 1.8138          | 3.8188 | 18.2782 |


### Framework versions

- Transformers 4.24.0
- Pytorch 1.13.0+cu117
- Datasets 2.6.1
- Tokenizers 0.13.2