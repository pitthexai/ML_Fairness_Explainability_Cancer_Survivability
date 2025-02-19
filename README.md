# Machine Learning Fairness and Explainability in Stage-Specific Cancer Survivability Prediction

This project develops machine learning (ML) models to predict cancer survivability with a focus on fairness and explainability, using data from the <a href="https://seer.cancer.gov/data/" target="_blank">SEER</a>. It addresses the need for tailored predictions that consider the different stages of several cancers, particularly bladder, breast, and prostate cancers.

## Abstract

While prior machine learning (ML) models for cancer survivability prediction often treated all cancer stages uniformly, cancer survivability prediction should involve understanding how different stages impact the outcomes. Additionally, the success of ML-powered cancer survival prediction models depends a lot on being fair and easy to understand, especially for different stages of cancer. Focusing on bladder, breast, and prostate cancers using SEER Program, we developed  fair and explainable ML strategies that aim to train separate models for each stage while they also advance fairness and explainability of those ML models. The current contribution advocates for the integration of fairness and explainability in these models to ensure equitable, fair, interpretable, and transparent predictions, thereby enhancing patient care and shared decision-making in cancer treatment.



## Installation

To set up this project, clone the repository.

```bash
git clone https://github.com/pitthexai/ML_Fairness_Explainability_Cancer_Survivability.git
```

## Features
+ <strong>Fairness Integration:</strong> Applies fairness algorithms to ensure unbiased predictions across different patient demographics. <br>
+ <strong>Explainability Tools:</strong> Utilizes SHAP and LIME to provide insights into the decision-making process of the models. <br>
+ <strong>Stage-Specific Predictions:</strong> Trains separate models for different cancer stages to enhance prediction accuracy.


## License
Apache-2.0 license
<p><strong>Note:</strong> All ML/AI fairness parts of our code, implementation, and documentation are derived from the <a href="https://aif360.res.ibm.com/" target="_blank">AI Fairness 360 - IBM</a> package and is subject to the terms of the Apache License 2.0.</p>

## SEER
<p>The entire dataset analyzed during the current study is available via <a href="https://seer.cancer.gov" target="_blank">Surveillance, Epidemiology, and End Results (SEER) Progra</a>.</p>

### Citation:

<p align="justify">This contribution is fully explained in the following paper published through <a href="https://www.sciencedirect.com/science/article/pii/S1386505625000395" target="_blank">International Journal of Medical Informatics</a>. Any publication using this work would require to cite the following paper:

  ```
  @article{kamble2025predicting,
  title={Predicting Cancer Survival at Different Stages: Insights from Fair and Explainable Machine Learning Approaches},
  author={Kamble, Tejasvi Sanjay and Wang, Hongtao and Myers, Nicole and Littlefield, Nickolas and Reid, Leah and McCarthy, Cynthia S and Lee, Young Ji and Liu, Hongfang and Pantanowitz, Liron and Amirian, Soheyla and others},
  journal={International Journal of Medical Informatics},
  pages={105822},
  year={2025},
  publisher={Elsevier}
}
```
## Contact Information
For any queries, reach out to Ahmad P. Tafti (tafti.ahmad@pitt.edu).
