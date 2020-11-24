### Hi everyone, here is my project of advanced econometircs! It is about left-children's education in China.

# Background
China's urbanization resulted in an enormous labor transfer from to the countryside to cities, creating a large number of left-behind children. The number of left-behind children in rural areas has reached 61.03 million in 2010, accounting for 37.7% of rural children and about 21.88% of all children. Among them, half of them Parents of left-behind children go out to work at the same time, which has a significant impact on the welfare and education of left-  behind children.
#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.01.10.png) 

# Problem Statement
Parental labor transfer affects left-behind children’s education significantly: 1) long-term separation from parents will lead to decreasing parents' care for children’s education inevitably, negatively affecting student’s academic performance. 2) parental labor transfer has increased family income and then strengthen the ability to invest in children's education, positively affecting children's academic performance. 

The paper is to research how parental transfer affect children’s academic performance overall and to qualify the two disparate influence.

# Literature Review
Many scholars believe that, parental labor labor will have an impact on the welfare and education of their children. The research on the quantitative relationship between labor transfer and education investment is relatively rich. In contrast, quantitative research on the impact of the parents' concern for their children's learning is not as rich.

Scholars differ on the definition of left-behind children in China. The article considers children aged 6 to 16 who have not lived together with their father or mother for more than ten months in the previous year as left-behind children.

# Methodology
## Data Sources
The dataset comes from the China Family Panel Studies (CFPS) in 2016, including 8427 observations, and 25 variables.

## Variables
#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.28.02.png)

## Descriptive Statistics
#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.32.29.png)


## Mmpirical Analysis
### (1) Grades = α + β1 Left + β2 Fedu + β3 Medu + β4 Selfept + β5 Parept + β6 Gender + β7 Age + εi                       
### (2) Eduexp = α + β1 Left + β2 Fedu + β3 Medu + β4 Edustage + β5 Parept + β6 Gender + β7 Finc + εi                     
### (3) Parcare = α + β1 Left + β2 Fedu + β3 Medu + β4 Edustage+ β5 Parept + β6 Gender + εi  

#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.41.13.png)


### Yi = β0 + β1 X1i + … + βk Xki + βk+1 W1i + … + βk+r Wri + εi
### Xki =α0 + α1 Z1i + … + α1+m Zmi + αm+1 W1i + … + αm+r Wri + εi
### Grades = α + β1 Parcare + β2 Eduexp + β5 Selfept + β7 Gender + β8 Age + εi

#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.44.36.png)

#### ![image](https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.50.56.png)

https://github.com/xudong-zhu2020/MPP-634/blob/MPP-634/截屏2020-11-25%20上午12.50.56.png

