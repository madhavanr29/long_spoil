
This repository contains the code and notebooks for the Clickbait Spoiling project. The project consists of two tasks: Task 1 is to classify clickbait types (phrase, passage, multi) and Task 2 is to generate spoilers for each clickbait type.

Directory Structure
baseline_milestone_2/task1

classification.ipynb: LSTM based model for Task 1 - Clickbait Classification.
classification_inference.ipynb: Inference notebook for the LSTM based model.
final_milestone3/task1

prompt1_ada.ipynb: GPT-3 based classifier for Task 1.
prompt2_ada.ipynb: GPT-3 based classifier for Task 1.
prompt3_curie.ipynb: GPT-3 based classifier for Task 1.
transformers_train_DistilBERT.ipynb: DistilBERT based classifier for Task 1.
transformers_train_bert_uncased.ipynb: BERT Uncased based classifier for Task 1.
transformers_train_longformer.ipynb: Longformer based classifier for Task 1.
transformers_train_roberta.ipynb: RoBERTa based classifier for Task 1.
final_milestone3/task2

multi
led.ipynb: Longformer Encoder Decoder model for 'multi' spoiler generation.
longt5.ipynb: LongT5 model for 'multi' spoiler generation.
longt5_eval.ipynb: Evaluation notebook for LongT5 'multi' spoiler generation.
t5_base.ipynb: T5 Base model for 'multi' spoiler generation.
passage
led.ipynb: Longformer Encoder Decoder model for 'passage' spoiler generation.
longt5.ipynb: LongT5 model for 'passage' spoiler generation.
longt5_eval.ipynb: Evaluation notebook for LongT5 'passage' spoiler generation.
t5_base.ipynb: T5 Base model for 'passage' spoiler generation.
phrase
led.ipynb: Longformer Encoder Decoder model for 'phrase' spoiler generation.
longt5.ipynb: LongT5 model for 'phrase' spoiler generation.
longt5_eval.ipynb: Evaluation notebook for LongT5 'phrase' spoiler generation.
t5_base.ipynb: T5 Base model for 'phrase' spoiler generation.
