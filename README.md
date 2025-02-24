# MSumBench
This is a repository for the paper "Towards Multi-dimensional Evaluation of LLM Summarization across Domains and Languages", which was submitted to ARR February, 2025.

We provide a subset of the **MSumBench** dataset, a multi-aspect summarization evaluation benchmark.

The subset contains the 2 or 3 instatnces for the six domains respectvively.

Here is an example of our dataset

uid: unique id

doc_id: the document id

dataset: the name of source dataset 

domain: the domain of source dataset

input_text: the input document

summary_model: used summarizer

summary: generated summary

fv_faithfulness: faithfulness score from fact verification

ka_completeness: completeness score from key-fact alignment

ka_conciseness: conciseness score from key-fact alginment
