[old page](old.md)

# Models
<details>
  <summary>1. case group SPTB</summary>
  <br> - were excluded "Pyrexia.in.labour.or.postpartum","FDCS.pregnancy.birth.weight..g.", "Uterine.Extensions", "Cervical.lacerations" (a lot of NA for SPTB)
  <br> - samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 166 | 8     | 158      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM,  number_Previous.late.miscarriage, number_Cervical.Surgery, number_previous.FDCS,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                              | 1      |
| mather + previous pregnancy        | 180 | 8     | 172      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM,  number_Previous.late.miscarriage, number_Cervical.Surgery, number_previous.FDCS                                                                                                                                                                                                                                               | 1      |
| scar                               | 177 | 8     | 169      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 1      |
  </pre>
</details>

<details>
  <summary>2. case group SPTB: excluded samples PBI == 1 and CL < 0.25 == 1 </summary>
  <br>  - were excluded "Pyrexia.in.labour.or.postpartum","FDCS.pregnancy.birth.weight..g.", "Uterine.Extensions", "Cervical.lacerations" (a lot of NA for SPTB)
  <br> - samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 145 | 6     | 139      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM,  number_Previous.late.miscarriage, number_Cervical.Surgery, number_previous.FDCS,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                              | 2      |
| mather + previous pregnancy        | 157 | 6     | 151      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM,  number_Previous.late.miscarriage, number_Cervical.Surgery, number_previous.FDCS                                                                                                                                                                                                                                               | 2      |
| scar                               | 153 | 6     | 147      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 2      |
  </pre>
</details>
<details>
  <summary>3. case group SPTB or PBI</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 144 | 22    | 122      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 3      |
| mather + previous pregnancy        | 155 | 23    | 132      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 3      |
| scar                               | 177 | 29    | 148      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 3      |
  </pre>
</details>
<details>
  <summary>4. case group SPTB or CL < 0.25</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 144 | 19    | 125      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 4      |
| mather + previous pregnancy        | 155 | 20    | 135      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 4      |
| scar                               | 177 | 25    | 152      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 4      |
  </pre>
</details>
<details>
  <summary>5. case group PBI</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 144 | 20    | 124      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 5      |
| mather + previous pregnancy        | 155 | 21    | 134      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 5      |
| scar                               | 177 | 23    | 154      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 5      |
  </pre>
</details>
<details>
  <summary>6. case group PBI (excluded samples with SPTB == 1)</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 140 | 18    | 122      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 6      |
| mather + previous pregnancy        | 151 | 19    | 132      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 6      |
| scar                               | 169 | 21    | 148      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 6      |
  </pre>
</details>
<details>
  <summary>7. case group CL < 0.25</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 144 | 17    | 127      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 7      |
| mather + previous pregnancy        | 155 | 18    | 137      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 7      |
| scar                               | 177 | 19    | 158      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 7      |

  </pre>
</details>
<details>
  <summary>8. case group CL < 0.25 (excluded samples with SPTB == 1) </summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 140 | 15    | 125      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                 | 8      |
| mather + previous pregnancy        | 151 | 16    | 135      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 8      |
| scar                               | 169 | 17    | 152      | Shortest.scar.distance.to.internal.os, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 8      |
  </pre>
</details>
<details>
  <summary>9: case group PBI: investigate "Largest.length","Depth", "Width.Largest", "RMT", "AMT"</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 44  | 9     | 35      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Largest.length, Depth, Width.Largest, RMT, AMT, Shortest.scar.distance.from.internal.os | 9      |
| mather + previous pregnancy        | 155 | 21    | 134     | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 9      |
| scar                               | 45  | 9     | 36      | Shortest.scar.distance.to.internal.os, Largest.length, Depth, Width.Largest, RMT, AMT, Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | 9      |
  </pre>
</details>
<details>
  <summary>10. case group CL < 0.25: investigate "Largest.length","Depth", "Width.Largest", "RMT", "AMT"	</summary>
  <br> samples were excluded if they have any parameters as NA
  <br>
  <pre>
| model                              | N   | cases | controls | features                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    | number |
|------------------------------------|-----|-------|----------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------|
| scar + mather + previous pregnancy | 44  | 8     | 36      | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.,  Shortest.scar.distance.to.internal.os, Largest.length, Depth, Width.Largest, RMT, AMT, Shortest.scar.distance.from.internal.os | 10     |
| mather + previous pregnancy        | 155 | 18    | 137     | White, Black, South.East.Asian, Others, Smoking.History, Previous.SPTB, Previous.PPROM,  Previous.late.miscarriage, Cervical.Surgery, Uterine.anomaly, History.of.recurrent.UTI.in.pregnancy,  Trial.of.intrumental.delivery, Uterine.Extensions, Cervical.lacerations, Pyrexia.in.labour.or.postpartum,  BMI, Age.at.del, Gravida, Parity, number_Previous.SPTB, number_Previous.PPROM, number_Previous.late.miscarriage,  number_Cervical.Surgery, number_previous.FDCS, FDCS.pregnancy.birth.weight..g.                                                                                                                                  | 10     |
| scar                               | 45  | 8     | 37      | Shortest.scar.distance.to.internal.os, Largest.length, Depth, Width.Largest, RMT, AMT,  Shortest.scar.distance.from.internal.os                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | 10     |

  </pre>
</details>

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
- ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) `(scar) + (mather + previous pregnancy)  parameters`

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









