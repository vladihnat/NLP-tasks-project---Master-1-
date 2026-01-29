# NLP-tasks-project---Master-1-
This repo is a self-contained project exploring diverse NLP tasks on a High-Quality Financial News Dataset. 
The data was found in [Kaggle](https://www.kaggle.com/datasets/sayelabualigah/high-quality-financial-news-dataset-for-nlp-tasks/data), it has been previously feed to a Mixtral 7X8B model to create `CompactedSummary`, `DetailedSummary`, `ParaphrasedSubject`	and `Impact`. This processed fields are going to be treated as labes for a supervised task. 

On this project we will first focus on two tasks, summarization and "impact" prediction, we aim to establish a teacher-student approach with the goal of improving previous results, either by founding a frugal approach and/or improving *faithfulness* regarding the teacher. 

Other possible tasks: 
- Paraphrase generation
- Multi-task model : One model that can generate all targets by instruction (Paraphrase the subject, Write a compact summary, Write a detailed summary, Write the impact)

