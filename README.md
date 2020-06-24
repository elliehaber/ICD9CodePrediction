# Predicting ICD-9 Codes Using Transfer Learning on Substructures of Patient Notes
Authors: Caroline Barker, Ellie Haber, and Andrew Liang

## Purpose
In our work we compare the multi-label classification performance
of pre-trained embeddings fine-tuned on ICD-9 diagnosis code prediction
using patient discharge summaries in the MIMIC-III dataset. The aim of our
work is to analyze how the classification task is affected and possibly 
improved by using different word embeddings and preprocessing methodologies. 
We evaluate the prediction task using a case study where the top-10 most 
frequently occuring ICD-9 codes are classified, and use BERT-base (Devlin et al. 2019) 
and BioBERT (Lee et al. 2019) embeddings fine-tuned on the first 512 tokens of patient 
discharge summaries as baseline models. These are compared to other BERT-base and 
BioBERT models fine-tuned on selectively extracted sections of discharge summaries: 
We show that models fine-tuned on Hospital Course sections achieve a 7\% increase 
in F1 score over our baseline models, with BioBERT HospCourse reaching the highest 
F1 score of 0.53, illustrating that using biomedical embeddings fine-tuned on 
certain subsections of MIMIC-III can improve performance for ICD-9 code prediction.

## Paper
<insert link here when uploaded>


