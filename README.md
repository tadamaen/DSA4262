# DSA4262
DSA4262 Repository is created for working on the individual assignments for the NUS Module DSA4262 - Sense-making case analysis: Health And Medicine

### Contents Of DSA4262 

1. Individual Assignment 1

    Individual Assignment 1 focuses on using data visualization to move from population-level evidence to a targeted, actionable mental health intervention. In this project, I explored depression as a public health     issue, motivated by its growing relevance in Singapore. Using multiple datasets, I constructed three progressive visualizations: a macro-level plot to identify demographic groups most at risk, a micro-level         analysis to examine key factors associated with depression among teenagers, and an actionable plot to identify Singapore estates where interventions could be most effectively deployed. Together, these 
    visualizations aim to support evidence-based policy design by highlighting who is most affected, why the issue persists, and where targeted resources should be prioritised.

2. Individual Assignment 2

    This project centers on predictive modelling using the `dreaddit_train` and `dreaddit_test` datasets. The primary goal was to develop a classification model capable of distinguishing between stressful and non-      stressful text. To achieve this, the pipeline encompassed data cleaning, exploratory data analysis, model development, and evaluation, alongside the generation of insights and a cost-benefit analysis. The           features considered included raw text, LIWC scores, sentiment scores, subreddit information, and DAL semantic features, ensuring a comprehensive approach to stress detection.

    Over the course of the project, 28 different models were explored, spanning classical machine learning, deep learning, and transformer-based architectures. Extensive hyperparameter tuning was conducted, and         hybrid models were designed to combine textual and numerical features. After rigorous experimentation and comparison, the Hybrid RoBERTa model emerged as the most effective solution, achieving an F1-Score of        0.8173 on the `dreaddit_test` dataset. This model successfully leveraged transformer-based embeddings while incorporating structured features to enhance predictive performance.

    Beyond model selection, interpretability was a key focus. SHAP and LIME analyses were applied to better understand the model’s decision-making process and to highlight the contribution of different features.        Misclassification patterns were examined across dimensions such as text length and subreddit category, yielding meaningful insights into the model’s strengths and limitations. These analyses provided a deeper       understanding of where the model performs well and where it struggles, informing potential improvements.

    The project also considered the broader implications of deploying such a model in real-world contexts. Ethical concerns, including bias, privacy, and responsible usage, were discussed in detail. Potential           applications were identified in counselling, educational services, and workplace well-being programs, where stress detection could provide valuable support. Finally, a roadmap was proposed for practical             implementation, outlining steps to improve generalizability, integrate with real-time systems, and establish safeguards for ethical deployment.
