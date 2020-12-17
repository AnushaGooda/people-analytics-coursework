## People Analytics Coursework

Task:

Creating a dashboard to help an analyst to discover which features are reasons for misclassification.
Highlighting possible sources of bias that results in bad quality decisions by the Machine Learning model.


**Directory Structure**

       people-analytics-coursework
        ├── requirements.txt
        ├── Group7SMM635.pdf
        ├── datasets
        │   └── cSVM.json
        ├── script
        │    ├── 01_visualization.ipynb
        │    └── output
        │        └── dashboard_tabs.html
        │        └── correlation_classified.jpeg
        │        └── correlation_misclassified.jpeg
        │        └── confusion_matrix.jpeg
        │           
        └── Key Findings.pdf
        └── README.md

**datasets**

`cSVM.json` -> Dataset as provided

**script**

`01_visualization.ipynb` -> Python code for creating the dashboard

**output**

`dashboard_tabs.html` -> Final dashboard with two tabs (Continuous and Categorical) <br />
`correlation_classified.jpeg` -> Correlation matrix between all continuous variables in case of correctly classifed individuals <br />
`correlation_misclassified.jpeg` -> Correlation matrix between all continuous variables in case of incorrectly classifed individuals <br />
`confusion_matrix.jpeg` -> Confusion matrix for True vs Predicted, Above and Below threshold <br />
