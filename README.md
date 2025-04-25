# Medical Summaries Evaluation
## Evaluating Model Outputs with NLP Metrics and Human Feedback

The task involved exploring the performance of an NLP model on summarization of  randomly selected 150 abstracts of medical articles. The purpose of this evaluation was to make medical knowledge more accessible by generating summaries that can be understood by non-medical personnel.

### Model Used: 
falconsai/medical_summarization: The model is a variant of the pre-trained T5 transformer model, fine-tuned for the task of summarizing medical texts. It is designed to generate concise and coherent summaries of medical documents, research papers, clinical notes and other healthcare related texts. 

### Dataset Used: 
test_data.csv: It contains 150 data samples randomly selected from the dataset used in the research paper: APPLS: Evaluating Evaluation Metrics for Plain Language Summarization.In this dataset, there are two types of text: abstract_text and target_text. The abstract_text is the medical article abstracts that will be your input to your language model. The target_text is the reference plain language summary.

### Conclusion
Overall, this task demonstrated that designing plain language summarization, specifically in the context of medical articles, requires a user-first approach. The evaluation of the model tested in this study highlighted critical gaps in readability, engagement and actionability. While the standard metrics helped measure word overlap and readability, human evaluation revealed the lack of engagement and the lack of actionable outcome for a layperson reading these texts. Hence, to truly make medical summaries accessible to a general reader, our evaluation needs to put end readers at the forefront of assessing these models. 

A full report for this evaluation can be found at medical_summaries_evaluation/EvaluatingMedicalSummaries.pdf
