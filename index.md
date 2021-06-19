[old page](old.md)

[old 2 page](old.md)

# Models
            
1. SPTB (with Shortest.cervical.length measurement)
2. SPTB
3. SPTB (excluded samples with PBI=1) (with with Shortest.cervical.length measurement)
4. SPTB (excluded samples with PBI=1)
5. SPTB  or PBI
6. SPTB or CL < 0.25
7. PBI
8. PBI cerclages
9. CL < 0.25

# Strategies
## Main comment:
Strategy I is more correct for presentation in the publication. Strategy II is presented here only to show that it does not work (that is, the desire to study features with a large number of missing values leads to a strong decrease in number of samples and the inability to build models correctly).

## I. Save more samples by removing features with a large number of missing values.
### Rule of preprocessing:
1. Good feature (saved in the data): If the feature contains 0 missing values.
2. Corrected feature (saved in the data after correction): If the feature contains <= 10% of missing values, then the missing values are filled with the average of the feature.
3. Excluded feature (removed from data): If the feature contains > 10% of missing values.
### Results

[ - Original data](str1_original.md)
[ - Excluded samples with Previous.SPTB == 1 (and sign Previous.SPTB respectively)](str1_exclSPTB.md)
[ - Excluded samples with Previous.PPROM == 1 (and sign Previous.PPROM respectively)](str1_exclPPROM.md)
[ - Excluded samples with Previous.late.miscarriage == 1 (and sign Previous.late.miscarriage respectively)](str1_exclLM.md)

## II. Save more features by removing samples with missing values.
### Rule of preprocessing:
1. Only those features are excluded if there are less than 6 "non-missing values" in the case group.
2. Then, samples are excluded if they contain at least one missing value in the data.
### Results
[ - Original data](str2_original.md)
[ - Excluded samples with Previous.SPTB == 1 (and sign Previous.SPTB respectively)](str2_exclSPTB.md)
[ - Excluded samples with Previous.PPROM == 1 (and sign Previous.PPROM respectively)](str2_exclPPROM.md)
[ - Excluded samples with Previous.late.miscarriage == 1 (and sign Previous.late.miscarriage respectively)](str2_exclLM.md)











