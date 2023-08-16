# NLP final project
NLP Course at Tel Aviv University

Course No: 03683077 

Project name: Improving ROUGE for Abstractive Summarization

Lecturer: Maor Ivgi

Participating students: Yousfan Ohad, Gal Eshed

**Project abstruct:**

Language models today can do different complex tasks, one of which is text-summarization. In order to evaluate the quality of the generated summary, different metrics are used that try to quantify syntactic and semantic properties of the summary and relate it to a reference summary and/or to the original text. A popular metric to do so is ROUGE, that compares overlaps of n-grams in the model generated summary to a reference summary. As human summaries are complex and expensive, the goal is to create models that can generate summaries that are as good as human summaries. An integrated part of that is the need to automate the ability to qualitatively evaluate the summary, and to do so as efficiently as possible. Despite it’s popularity, ROUGE has several flaws, such as giving a high score to summaries that are not factual or not coherent. We aim to improve ROUGE by mitigating some of it’s flaws while still keeping it’s qualities. We examine regularization factors that refer to the original text and to the reference summary in a semantic and extractive manner to adjust the final ROUGE score. We show that we get better results compared to the classic ROUGE metrics.

**Running the code:**

The data used for this project is the annotated XSUM dataset which can be found [here](https://aclanthology.org/2020.acl-main.173.pdf)
with the [relevant git](https://github.com/google-research-datasets/xsum_hallucination_annotations).
Use of other python packeges is detailed in the notebook.
