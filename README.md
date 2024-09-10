In this repository, you can find the data, code, and figures related to the paper: AUTOLYCUS: Exploiting Explainable Artificial Intelligence (XAI) for Model Extraction Attacks against Interpretable Models (published in PETs 2024 with artifacts reproduced badge).

1. You can experiment on the proposed attack using ipynb files. Experiments evaluates the impacts of number of explored features (1), inherent dataset complexity (2), number of queries (3) and size of auxiliary dataset (4) on model extraction attacks against interpretable models.

2. Datasets can be included in the code directly or manually added to the 'data' folder. Make sure they follow a similar format to other datasets for explainer compatibility. For adding your own datasets please navigate to load_dataset method in utils and configure the variables similar to built-in datasets.

3. 'requirements.txt' provides the libraries and their version numbers as used in our work.

IMPORTANT: For more detailed documentation of the experiments and software&hardware requirements, please refer to template.md

We welcome suggested improvements for streamlining the code and enhancing the attack. During the standardization, we realized there are many bugs, runtime issues and we hope to resolve them in time. For further questions, suggestions and improvements about the code, email abdullahcaglar.oksuz@case.edu.
