# Clinic_Data_Description
Data explorations within clinical research
## 1.The Quantitative data
The **Group Numberous Test** chunk


```{r }
#age
tb=Num_table("age","type",df)
as.data.frame(tb)
```
**df** is a dataframe, that contains *age* and *type* inside.

The *Num_table* funtions has three parameters and the first is varible(**Varible is a continuos data**), the second is response.(**The response is a factor**)

Refernce：[Parametric and Non-parametric tests.](https://www.healthknowledge.org.uk/public-health-textbook/research-methods/1b-statistical-methods/parametric-nonparametric-tests)


## 2.The Categorical data
The **Table Test** chunk


```{r }
#gender
tb=chi_table("gender","lym",df)
as.data.frame(tb)
```

**df** is a dataframe, that contains *gender* and *lym* inside.

The *chi_table* funtions has three parameters and the first is varible, the second is response.**Both of them are factors**


###[Key non-parametric tests](chrome-extension://ikhdkkncnoglghljlkmcimlnlhkeamad/pdf-viewer/web/viewer.html?file=https%3A%2F%2Fwww.sheffield.ac.uk%2Fpolopoly_fs%2F1.579191!%2Ffile%2Fstcp-karadimitriou-normalR.pdf)

## 3.Linear regression

## 4.Binariy logistic regression
###[LOGIT REGRESSION | R DATA ANALYSIS EXAMPLES.](https://stats.idre.ucla.edu/r/dae/logit-regression/)

###[How to Perform a Logistic Regression in R.](https://datascienceplus.com/perform-logistic-regression-in-r/)
