
# (One-parametr) Comparison between the Control and Case groups was by chi- square test for categorical variables and Wilcoxon test for continuous variables

![Image](excl_prevLateM_common_one_1.png)

# (Multi-parametr) logistic regression (significance of coefficients)
![Image](excl_prevLateM_common_all_1.png)



# Results
## Model
- GLM

## Types of building (LOOCV - pessimistic AUC)
- *LOOCV* (The purpose of this check is to make sure that the chosen method of the model does not lead to its overfitting and allows it to be applied to other data):
1. Each point is excluded from the dataset
2. The model is built using the remaining points
3. Using the constructed model, the thrown out point receives a prediction (the probability of belonging to a class of cases)
4. The final ROC is based on these predictions

## Colors
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `(scar) parameters`
- ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) `(mather + previous pregnancy) parameters`
- ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) `(scar) + (mather + previous pregnancy) parameters`

## AUCs
![Image](excl_prevLateM_fig.png)

