# product_matching
Here are some insights and manipulations gotten/done from this analysis.

1. Null Value Challenge: Dealing with a significant number of null values posed a major challenge in this analysis.

2. Null Replacement: Null values were replaced with blanks to retain data patterns.

3. Consistent Cross-Validation: Initial accuracy tests revealed consistent mean scores across different models during cross-validation, indicating model stability.

4. Low Cross-Validation Variability: The low cross-validation standard deviations (0.003 to 0.006) implied minimal performance variability across different data subsets.

5. F1 Score Variability: Models like logistic regression and decision tree achieved an F1 score of 0.86, excelling in precision and recall, while others like KNN and random forest had slightly higher F1 scores.

6. Precision Strength: Models demonstrated high precision for "non-matching" instances, signifying accurate positive predictions.

7. Recall Disparities: Logistic regression achieved perfect recall for "non-matching" cases, whereas other models maintained high precision and recall for those cases.

8. Model Selection: Through initial accuracy tests, random forest emerged as the most promising model among the alternatives.

9. Performance Drop: On test data, the F1 score of the chosen random forest model decreased to 0.66, pointing to potential generalization challenges.

10. Gold Standard Evaluation: The model's performance on gold standard data was below the achieved scores on validation data, suggesting room for improvement and highlighting the need to align with reference standards.

