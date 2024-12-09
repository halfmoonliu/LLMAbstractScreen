# Leveraging LLMs to Facilitate Abstract Screening for Systematic Review

## Abstract 
Title and abstract screening has become a bottleneck for knowledge synthesis effort as the number of published research papers grows rapidly. This repository demonstrates methods to leverage Large Language Models (LLMs) to facilitate this crucial but labor intensive step of title and abstract screening for conducting systematic and scoping reviews.


## Background
Systematic and scoping reviews are crucial for synthesizing research findings on various topics and guiding future research. A typical systematic or scoping review that gathers relevant papers for knowledge synthesis involves the following steps: keyword search on research databases (e.g. PubMed), title/abstract screening, full text review, data extraction and analysis. However, as the number of published research papers increases, even a carefully curated keyword search in databases, with the help of experienced librarians, can return thousands of potentially relevant papers. Tremendous time is needed in the title/abstract screening phase and the rate of actually relevant paper is low. For example, in our recent scoping review on artificial intelligence (AI) application in clinical trial participant recruitment and retention (Hong et al., in preparation) [1], our keyword search from five databases resulted in more than 18,000 research papers. However, only about 0.5% of those were included in the final analysis. 


Recent advancements in LLMs show promise in improving the abstract screening process. Studies have explored prompting LLMs to classify abstracts as “included” or “excluded”, with reported overall accuracies ranging from .85 to .95 and sensitivity from .76 to .93 on different datasets [2-3]. Wilkins (2023)4 applied a  “chain of thoughts” approach, or breaking a prompt into several questions to guide LLM reasoning, achieving an accuracy of .84 and a sensitivity of .71. Some researchers, such as Akinseloyin et al. (2024)5 and Wang et al. (2024)6, proposed generating relevance scores for candidate abstracts, using these scores to decide on inclusion. However, no existing pipelines have been thoroughly tested on different research topics that consistently outperforms human abstract screening. Additionally, the risk benefit analysis of potential omission of relevant papers and time save has not yet been fully addressed.


The goal of this project is to develop a pipeline to leverage LLMs for title/abstract screening for systematic and scoping review, addressing the limitations of current methods.  The expected deliverables are as follows: 1) A proof-of-concept pipeline for LLM-assisted paper screening for systematic/ scoping reviews. 2) A journal/conference article summarizing the results and findings.

## References

1. Hong C et al. (In preparation), Artificial Intelligence in Clinical Trial Participant Recruitment and Retention: A Scoping Review Protocol.
2. Guo E, Gupta M, Deng J, et al. Automated Paper Screening for Clinical Reviews Using Large Language Models: Data Analysis Study. J Med Internet Res, 2024;26:e48996.
Li M, Sun J, Tan X, et al. Evaluating the Effectiveness of Large Language Models in Abstract Screening: A Comparative Analysis, 27 March 2024, PREPRINT available at Research Square.
