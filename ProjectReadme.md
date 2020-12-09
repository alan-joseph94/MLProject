Here is where you include:
  - Background on your code files
  - How to run your code, guide to install any additional packages
  - Results, interpretation and reflection
  



How to Run

1. Clone my git project repository
2. Open jupyter notebook and upload UCI_Credit_Card.CSV file. 
3. Then open Alan_Credit_Project.ipynb & run the notebook. 


Results & Interpretation 


I investigated the data, visualized some of the features, checked data imbalance and then split out data into train and test sets. I then compared the different models and observed their accuracy scores. :

- GradientBoostingClassifier : 68.5%
- RandomForestClassifier : 80.3%
- LogisticRegression : 80.6%
- GaussianNaiveBayes : 69.6%
- SupportVectorClassifier : 81.4%

I can therefore conclude that the SVC model was the most accurate and hence it is a good model to use. However, the RandomForestClassifier & LogisticRegression models also were close enough. 
I set out to compare ML Algorithm to see which one had the highest accuracy on the credit default dataset and I think I was successful. I did not attempt cross-validation or try to find a better threshold based on my model since I thought they might be out of the scope of this project.



Reflection

I am not too sure if I deviated or did not include something that was required. But what I want to say after working on this project is -  WOW, I learned a lot. Simple thing such learning how to work the axes in Section 2 and how to unwrap my data were eye-openers. When I first started this class I was not too confident about being able to cope with the regular material, let alone work on a project by myself, but I am so happy to have come this far. Although my project might not be as sophisticated or my interperations incorrect, I am thrilled to have done what I did. Thank you Prof. Yves.