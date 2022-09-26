# Health-cost-prediction-with-regression

It's predicting healthcare costs using a regression algorithm.

Given a dataset that contains information about different people including their healthcare costs.

It has converted categorical data to numbers and were used 80% of the data as the `train_dataset` and 20% of the data as the `test_dataset`.

`pop` off the "expenses" column from these datasets to create new datasets called `train_labels` and `test_labels`. These labels were used when training this model.

Model has been created and trained with the `train_dataset`. The final cell have used the unseen `test_dataset` to check how well the model generalizes.

The final cell also predicts expenses using the `test_dataset` and graph the results.
