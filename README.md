This report evaluates the suitability of three popular manipulative-language taxonomies for
both human annotation and LLM-based classification of political advertisements. Although
prior research has applied manipulation taxonomies in manipulative language classification
tasks, little attention has been given to whether the taxonomies themselves are well suited to
support consistent annotation or automated detection. This project addresses that gap through
a comparative evaluation of three established manipulation taxonomies: Noggle’s taxonomy,
Simon’s taxonomy, and Information Manipulation Theory 2 (IMT2).

Using a dataset of 600 advertisements taken from the ’Comparable 2022 General Election
Advertising Datasets from Meta and Google’ dataset, the taxonomies were evaluated through
human annotation, zero-shot and few-shot LLM classification, and the taxonomy quality metrics
established by Unterkalmsteiner and Abdeen.

Human annotators showed a preference for Noggle’s taxonomy, which achieved the strongest
comprehensiveness and intra-model reliability. In contrast, IMT2 yielded the strongest LLM
classification performance, despite weak agreement across models. Few-shot prompting did not
consistently improve results.

The findings reveal a trade-off between human interpretability and model performance,
suggesting that taxonomies better suited to human reasoning may not necessarily be success-
fully implemented by LLMs. Alongside this, the results indicate that taxonomy design itself
influences classification outcomes and should be treated as an object of evaluation rather than
assumed as a fixed foundation for manipulation detection.
