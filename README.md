# Introduction

Eating disorders, such as anorexia nervosa, bulimia nervosa, and binge eating disorder, are serious mental health conditions characterized by abnormal eating habits and distorted body image. These disorders often stem from a combination of genetic, psychological, and social factors. Individuals may restrict food intake, engage in binge eating followed by purging behaviors, or compulsively overeat. Eating disorders can have devastating effects on physical health, leading to malnutrition, electrolyte imbalances, and organ damage. Psychological impacts include depression, anxiety, and low self-esteem. Treatment typically involves a combination of therapy, nutritional counseling, and medical supervision to address both physical and mental aspects of the disorder.

# Results

## Performance Metrics for Section A

| Metric | MNB   | LSVM  | LogReg | NN    |
|--------|-------|-------|--------|-------|
| MAE    | 2.341 | **1.974** | 2.044  | 2.586 |
| MZOE   | 0.675 | 0.701 | **0.672** | 0.765 |
| MAE_m  | 1.745 | **1.560** | 1.627 | 1.783 |
| GED    | 1.838 | **1.361** | 1.542 | 2.337 |
| RS     | 2.579 | **1.987** | 2.432 | 2.745 |
| ECS    | 3.017 | **1.627** | 2.148 | 2.801 |
| SCS    | 1.914 | **1.418** | 1.623 | 2.240 |
| WCS    | 1.914 | **1.418** | 1.623 | 2.240 |

## Performance Metrics for Section B

| Metric | MNB   | LSVM  | LogReg |
|--------|-------|-------|--------|
| MAE    | 3.360 | **2.127** | 2.399  |
| MZOE   | 0.815 | **0.619** | 0.731 |
| MAE_m  | 2.286 | 1.974 | **1.791** |
| GED    | 3.677 | **2.570** | 2.613 |
| RS     | 3.694 | 3.071 | **2.992** |
| ECS    | 3.185 | **2.714** | 2.581 |
| SCS    | 4.278 | **2.487** | 2.907 |
| WCS    | 3.823 | **2.497** | 2.524 |

## Performance Metrics For Section C

| Metric | LogReg | LSVM  | RF    | GB    |
|--------|--------|-------|-------|-------|
| MAE    | **2.185** | 2.370 | 2.401 | 2.464 |
| MZOE   | **0.630** | 0.657 | 0.687 | 0.784 |
| MAE_m  | 1.992  | 2.035 | 2.005 | **1.780** |
| GED    | 2.660  | 2.743 | 2.730 | **2.576** |
| RS     | 3.000  | 3.071 | 3.025 | **2.758** |
| ECS    | 2.888  | 2.672 | 2.527 | **2.288** |
| SCS    | **2.735** | 2.999 | 2.946 | 3.082 |
| WCS    | **2.494** | 2.634 | 2.878 | 2.647 |

## Performance Metrics for Section D

| Model | LogReg | LSVM  | RF    | GB    |
|-------|--------|-------|-------|-------|
| MAE   | 2.005  | 1.950 | 1.974 | **1.849** |
| MZOE  | 0.696  | **0.672** | 0.755 | 0.756 |
| MAE_m | 1.542  | 1.593 | 1.548 | **1.413** |
| GED   | 1.580  | 1.512 | 1.607 | **1.387** |
| RS    | 2.222  | 2.245 | 2.091 | **1.975** |
| ECS   | 2.547  | 2.423 | 2.022 | **1.585** |
| SCS   | **1.439** | 1.511 | 1.701 | 1.446 |
| WCS   | 1.422  | **1.416** | 1.551 | 1.666 |

## Performance Metrics for Section E

| Metric | LogReg | LSVM  | RF    | GB    |
|--------|--------|-------|-------|-------|
| MAE    | 2.125  | 2.026 | 1.943 | **1.875** |
| MZOE   | 0.703  | **0.682** | 0.760 | 0.756 |
| MAE_m  | 1.638  | 1.668 | 1.580 | **1.502** |
| GED    | 1.582  | 1.545 | 1.756 | **1.492** |
| RS     | **2.145**  | 2.323 | 2.425 | 2.432 |
| ECS    | 2.642  | 2.353 | 2.046 | **1.600** |
| SCS    | 1.567  | **1.430** | 1.672 | 1.532 |
| WCS    | 1.717  | 1.515 | 1.778 | **1.403** |

## Model Abbreviation Glossary

| Abbreviation | Full Form                   |
|--------------|-----------------------------|
| LogReg       | Logistic Regression         |
| NMB          | Multinomial Naive Bayes     |
| LSVM         | Linear Support Vector Machine |
| NN           | Neural Network              |
| RF           | Random Forest               |
| GB           | Gradient Boosting           |


