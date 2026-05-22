# Lalonde-Job-training-programme

# Lalonde Dataset Analysis  

This project analyses the Lalonde dataset using Python.

The conducted study looked at the effectiveness of a job training programme on the earnings (here: considered the treatment) of individuals after completion.

** Robert Lalonde, "Evaluating the Econometric Evaluations of Training Programs", American Economic Review, Vol. 76, pp. 604-620 **


## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
## Structure

## Dataset information:

# 

Info is retrieved from: https://rdrr.io/cran/MatchIt/man/lalonde.html
Treatment (treat): participated in training (1/0)
Outcome (re78): earnings after participation in the programme
Covariates: age, education, race, material status, past earnings (re74, re75)

** Note: Treated vs control groups are not comparable
Strong selection bias
A data frame with 614 observations (185 treated, 429 control). There are 9 variables measured for each individual.

"treat" is the treatment assignment (1=treated, 0=control).

"age" is age in years.

"educ" is education in number of years of schooling.

"race" is the individual's race/ethnicity, (Black, Hispanic, or White). Note previous versions of this dataset used indicator variables black and hispan instead of a single race variable.

"married" is an indicator for married (1=married, 0=not married).

"nodegree" is an indicator for whether the individual has a high school degree (1=no degree, 0=degree).

"re74" is income in 1974, in U.S. dollars.

"re75" is income in 1975, in U.S. dollars.

"re78" is income in 1978, in U.S. dollars.

"treat" is the treatment variable, "re78" is the outcome, and the others are pre-treatment covariates.

References
Lalonde, R. (1986). Evaluating the econometric evaluations of training programs with experimental data. American Economic Review 76: 604-620.

Dehejia, R.H. and Wahba, S. (1999). Causal Effects in Nonexperimental Studies: Re-Evaluating the Evaluation of Training Programs. Journal of the American Statistical Association 94: 1053-1062.

