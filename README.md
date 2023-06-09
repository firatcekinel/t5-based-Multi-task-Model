# t5-based Multi-task Model

This study primarily focuses on designing a multi-task explainable misinformation detection model. To be more specific, a fact-checking model is trained on veracity prediction and text summarization tasks simultaneously. The generated summaries are derived from evidence documents, serve as justifications for the model’s veracity prediction.

You need to install the packages listed in "requirements.txt" file to execute the model. We also presented single-task t5-based summarization and classification models for comparison. 

We evaluated our model on the e-FEVER dataset (Stammbach and Ash, 2020) is a subset of the original FEVER dataset (Thorne et al., 2018) and consists of 67687 claims with evidence documents retrieved using the DOMLIN system. In addition to claims and evidence documents, the authors published the summaries generated by the GPT-3-based model for each claim. Hence, these summaries were leveraged as ground-truth explanations to compare our model’s decision-making process with the GPT-3-based model.

