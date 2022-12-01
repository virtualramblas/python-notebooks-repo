# DRPreter Paper Evaluation
A notebook to evaluate (training and test) the **DRPreter: Interpretable Anticancer Drug Response Prediction Using Knowledge-Guided Graph Neural Networks and Transformer** [paper](https://www.mdpi.com/1422-0067/23/22/13919).  
![DRPreter](https://user-images.githubusercontent.com/68269057/198502117-785291dd-af73-40d3-8fed-0e8881404119.png)  
DRPreter learns cell line and drug information with graph neural networks; the cell-line graph is further divided into multiple subgraphs with domain knowledge on biological pathways. A type-aware transformer in DRPreter helps detect relationships between pathways and a drug, highlighting important pathways that are involved in the drug response.  
A GPU runtime is required to execute the code in this notebook.