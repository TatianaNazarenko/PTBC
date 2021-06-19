
# (One-parametr) Comparison between the Control and Case groups was by chi- square test for categorical variables and Wilcoxon test for continuous variables

![Image](./data/one_param_tests.png)

# (Multi-parametr) logistic regression (significance of coefficients)
![Image](./data/multiparam_glm.png)



# Results
## Models
*(catch different data features)*
- GLM
- ExtraTrees

## Types of building (LOOCV - pessimistic AUC, Full - optimistic AUC)
- *LOOCV* (The purpose of this check is to make sure that the chosen method of the model does not lead to its overfitting and allows it to be applied to other data):
1. Each point is excluded from the dataset
2. The model is built using the remaining points
3. Using the constructed model, the thrown out point receives a prediction (the probability of belonging to a class of cases)
4. The final ROC is based on these predictions

- *Full*: The model is built on all data (the AUC estimates in this case are overestimated, since the model overfitted)

## Colors
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `(scar) parameters`
- ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) `(mather + previous pregnancy) parameters`
- ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) `(scar) + (mather + previous pregnancy) parameters`

## 1. SPTB
![Image](./data/1common.png)
## 2. SPTB: excluded samples PBI == 1 and CL < 0.25 == 1
![Image](./data/2common.png)
## 3. SPTB or PBI
![Image](./data/3common.png)
## 4. SPTB or CL < 0.25
![Image](./data/4common.png)
## 5. PBI
![Image](./data/5common.png)
## 6. PBI (excluded samples with SPTB == 1)
![Image](./data/6common.png)
## 7. CL < 0.25
![Image](./data/7common.png)
## 8. CL < 0.25 (excluded samples with SPTB == 1)
![Image](./data/8common.png)
## 9: PBI: investigate "Largest.length","Depth", "Width.Largest", "RMT", "AMT"
![Image](./data/9common.png)
## 10. CL < 0.25: investigate "Largest.length","Depth", "Width.Largest", "RMT", "AMT"
![Image](./data/10common.png)


# Fig for main parameters
![Image](./data/main.png)


# --
![Image](./data/amrita_fig.png)
