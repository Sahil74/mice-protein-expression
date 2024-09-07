# Protein Expression Classification for Down Syndrome
  
  ## Abstract

- Down syndrome, a chromosomal abnormality affecting approximately 0.1% of live births globally, arises from the presence of an extra copy of chromosome 21.
  This genetic anomaly results in the overexpression of specific genes, which disrupt normal cognitive pathways and impair learning and memory. To address this, our study analyzed
  77 differentially expressed proteins in trisomic mice exposed to context fear conditioning (CFC). By leveraging decision tree and random forest classification models, we identified
  key proteins that may be targeted to develop effective drugs aimed at improving cognitive functions in individuals with Down syndrome.

  ## Problem Statement
- Protein expression classification is complex, requiring a balance between accuracy and efficiency. With 77 protein expressions measured in eight classes of control and Down syndrome mice, 
  the challenge is to identify discriminant proteins across these classes, making it a multi-class classification problem.

![Diagram](./'Picture 1.png')

  ## Technical Requirements
- Applied Mathematics: Essential for calculating accuracy and other metrics.
- Programming: Python for implementing machine learning algorithms.
- Machine Learning Knowledge: Familiarity with classification algorithms and techniques.
- Data Modeling and Evaluation: Expertise in data modeling and performance evaluation.

![Diagram](./'Picture 2.png')

  ## Performance

- The classification models demonstrated high efficacy in identifying key proteins. 
- The Random Forest model significantly outperformed the Decision Tree model, with a near-perfect Recall, F1-Score, and Precision of 0.99 compared to 0.84 for the Decision Tree. 
- This performance indicates the Random Forest's superior capability in distinguishing important proteins.

  ##  Conclusion

- The Random Forest model demonstrated superior performance over the Decision Tree in identifying crucial proteins related to cognitive functions in Down syndrome. 
  Both models highlighted key proteins involved in learning pathways, with the Random Forest providing more accurate predictions.
