# Bootcamp_projects
Data Science projects

1. Capstone Project 1  -> Bright Motor Company

2. Capstone Project 2  -> Flight Delay Dataset

3. Mini Project 1 -> Zomato 

4. Mini Project 2  -> Labour Earning Prediction

5. Mini Project 3  -> Viva Credit

## Course work notebooks -

1. Grid_Search.ipynb -> Randomly generated dataset using make_classification() <br>
    ```
    grid_search = GridSearchCV(
        dt,
        param_grid,
        scoring = 'accuracy',
        verbose = 1,
        n_jobs = 8,
        return_train_score = True
    )
    ```

2. K_Fold_Analysis.ipynb -> load_iris dataset from sklearn.datasets <br>
    Compare Different K Values -
	1. Run cross-validation with K = 3, 5, 10
    2. Plot the accuracy scores for each K.
    3. Comment on performance and runtime.

3. 25_06_2025.ipynb -> Heart dataset <br>
    Cross-Validation with Multiple Models -
	1. Use Logistic Regression, Random Forest, K-Nearest Neighbors and SVM.
	2. Perform 10-fold cross-validation on all three.
	3. Create a bar chart showing average accuracy of each model.
