# Sentence Classification

This repository contains training and evaluation data as described in the article "Automated Knowledge Extraction from IS Research Articles Combining Sentence Classification and Ontological Annotation".

The data can be freely used for scientific projects.

For questions regarding commercial usage, please contact the owner of the repository.

The preferred citation for this data is: ...

# Data Descriptions

## Dataset_Training.xlsx
This file contains 3,268 sentences from open-access AIS8 articles (AIS 2021). We sampled these sentences from 117 articles and classified each sentence into one of three categories: belongs_to_article, related_work, and background_information.
This dataset was annotated by the author of the paper.

## Dataset_Evaluation.xlsx
This file contains 1,000 sentences from open-source AIS8 articles (AIS 2021). We sampled these sentences from 117 articles and classified each sentence into one of three categories: belongs_to_article, related_work, and background_information.
This dataset was annotated by the author of the paper and a master student in Information Systems. 
Both annotators independently assigned the same labels in 889 out of 1,000 cases. This resulted in a Cohen's Kappa of 0.77 and falls into the category of substantial agreement (Landis & Koch, 1977; SciKit Learn, 2022). The annotators assigned finally agreed-upon labels for sentences with deviating classes throughout discussing the results.

## Sentence Classification Framework.xlsx
This file contains a framework that was used as a codebook for manually classifying the sentences, providing examples for the individual sentence classes.

## Article_Information.xlsx
This file contains references to the 117 articles from AIS8 (AIS 2021). The sentences in this repository were sampled from these articles.


# References

AIS (2021), Senior Scholars’ Basket of Journals, https://aisnet.org/page/SeniorScholarBasket, Accessed: 15.11.2021.

Landis, J.R. & Koch, G.G. (1977), ‘The Measurement of Observer Agreement for Categorical Data’, Biometrics 33(1), p. 159.

SciKit Learn (2022), Cohen’s kappa: a statistic that measures inter-annotator agreement, https://scikit-learn/stable/modules/generated/sklearn.metrics.cohen_kappa_score.html, Accessed: 10.3.2023.


