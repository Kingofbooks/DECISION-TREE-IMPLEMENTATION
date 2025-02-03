# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: ARYAN SHARMA

*INTERN ID*: CT08PBS

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

DESCRIPTION:
ML Internship Project - Decision Tree Model Build Using Scikit-Learn

Internship Institution: CODTECH

Task: Build and visualize a Decision Tree model using Scikit-Learn to classify or predict outcomes on any chosen dataset.

Tools & Technologies Used:
    Programming Language: Python
    Libraries: Scikit-Learn, Pandas, NumPy, Matplotlib, Seaborn
    Dataset: Iris Dataset
Implementation Steps:
      -> Data Importing & Exploration:
          The Iris dataset was loaded using pandas.read_csv().
          The dataset contained 150 rows and 6 columns: Id, SepalLengthCm, SepalWidthCm, PetalLengthCm, PetalWidthCm, and Species.
          Data types, missing values were checked and statistical analysis was done (.describe(), .info.) 
      -> Data Preprocessing:
          There were no missing or noisy values in the dataset.
          The Id column was dropped as it did not affect classification. 
      -> Data Visualization:
          Histograms were plotted for SepalLengthCm, SepalWidthCm, PetalLengthCm, and PetalWidthCm in order to analyze the distribution of the features. 
          Scatter Plots were used to view the relationships between Sepal and Petal dimensions across species.
      -> Building the Decision Tree Model:
          The data set was split into training and testing sets using train_test_split().
          The Decision Tree Classifier was trained using the DecisionTreeClassifier() from Scikit-Learn.
          Model performance was evaluated by looking at the accuracy scores.
      -> Decision Tree Visualization:
          The plot_tree() function was used to visualize the trained model, shedding the light on how the features were responsible for the classification decisions.
      -> Outcome:
          The model was able to classify correctly between Iris species based on Sepal and Petal measurements. The decision tree plot also showed the importance of the features and how decisions were made. 
      -> Conclusion: 
          This task imparted practical knowledge of data preprocessing, visualization, and empirical machine learning using Decision Trees.
