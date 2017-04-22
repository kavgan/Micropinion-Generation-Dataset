# Micropinion-Generation-Dataset
Dataset for Micropinion Generation - Ganesan &amp; Zhai 2012

This dataset is based on user reviews from CNET. The reviews are on products from various categories like tv, cell phones, gps etc. You will find two versions of the dataset :- "raw" and "pre-processed".  The "raw" folder has the original reviews from CNET without any pre-processing (each review is delimited by "$$;"). The "pre-processed" folder contains sentences from the full review section of the reviews. All the pros and cons from the original reviews are omitted in this version and this was the version used for summarization (See Section 5.1 of paper).  In addition in the pre-processed version, a simple sentence splitter was used to split the review texts into different sentences. 

# Citation
If you use this dataset for your own research please cite the following to mark the dataset: 

```
Ganesan, K. A., C. X. Zhai, and Evelyne Viegas, " Micropinion Generation: An Unsupervised Approach To Generating Ultra-Concise Summaries Of Opinions", Proceedings of the 21st International Conference on World Wide Web 2012 (WWW '12).
```

```
@inproceedings {Ganesan2012a,
	title = {Micropinion Generation: An Unsupervised Approach to Generating Ultra-Concise Summaries of Opinions},
	booktitle = {Proceedings of the 21st International Conference on World Wide Web 2012 (WWW {\textquoteright}12)},
	year = {2012},
	abstract = {This paper presents a new unsupervised approach to generating ultra-concise summaries of opinions. We formulate the problem of generating such a micropinion summary as an optimization problem, where we seek a set of concise and non-redundant phrases that are readable and represent key opinions in text. We measure representativeness based on a modified mutual information function and model readability with an n-gram language model. We propose some heuristic algorithms to efficiently solve this optimization problem. Evaluation results show that our unsupervised approach outperforms other state of the art summarization methods and the generated summaries are informative and readable. },
	author = {Kavita Ganesan and ChengXiang Zhai and Evelyne Viegas}
}}
```
