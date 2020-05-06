## 1. Person 1 has hazard h_1(t) = 1, and Person 2 has hazard h_2(t) = 2. What is the probability of dying within the first year for each patient?

<img src="https://render.githubusercontent.com/render/math?math=S(t)=exp{\int_0^t h(s) ds}">

## A. [0.63, 0.86]
## Why: 1-S1(1) = 1- exp(-1) =0.63, 1-S2(1) = 1- exp(-2) =0.86, 

## 2. Let T > 0T>0. For patient 1, let the survival function be S_1(t) and the hazard function be h_1(t). For patient 2, let the survival function be S_2(t) and the hazard function be h_2(t). You see that S_1(T) > S_2(T)S. The survival probability of patient 1 at time T is higher than the survival probability of patient 2 at time T. Which of the following is true about the hazard of patient 1 and 2 at time T?
Hint: <img src="https://render.githubusercontent.com/render/math?math=S(t)=exp{\int_0^t h(s) ds}">

## A. None of those
## Why: So just because you know S(T) at one point does not say anything about h(T) at that point, since S(T) also depends on what happened from time t=0 up to time t=T.

## 3. Now assume that the hazards for patient 1, h_1h and for patient 2, h_2h are proportional to each other. Also assume that S_1(T) > S_2(T) for some T > 0. Then which of the following is true about the hazards?
## A. h_1(T) < h_2(T)
## Why: Since the hazards are proportional, we know that they cannot cross each other when we vary the time T.

## 4. You’ve fit a Cox model on 2 features: age and smoking status.

The coefficients of these features are:
\beta_{age} = 0.9 and \beta_{smoker} = 10.0

What is the hazard ratio between Person 1, a 40 year old non-smoker, and Person 2, a 30 year old smoker?

Recall that Cox Proportional Hazards assumes a model of the form:
## A. 0.36
## h_1(t)/h_2(t) = exp(0.9*40)/exp(0.9*30+10*1) = e(36-37) = e(-1) = 0.36.

## 5. You’ve fit a cox model and have the following coefficients:
beta_female = -1.0, beta_age = 1.0, beta_BP = 0.6.
## Which of the following interpretations is most correct?
## A. All other things held equal, being a female decreases your risk

## 6. Assume h_1(t) = t, and h_2(t) = 1.0. At which time T > 0 does S_1(T) = S_2(T)?
## A. 2
## the cumulative hazard for h_1(t) is 1/2t^2, h_2(t) is t then
## When is the time 1/2t^2=t then t = 0 or 2.

## 7. Using the Nelson-Aalen estimator estimate H(7), the value of the cumulative hazard at t=7 for this dataset.
ID, outcome
1, 3
2, 4
3, 8
4, 6+
## A. 7/12

## 8. Which risk assignments would make this pair concordant?
 Patient 1, Patient 2
T, 10, 5+
## A. The pair is not permissible.

## 9. Compute the Harrell C-index for the following dataset and risk scores:
ID, outcome, Score 
1, 4, 1.6
2, 6+, 1.2
3, 5, 0.8
4, 7, 0.1
## A. 0.8
## Why: permissible pair is (1,2), (1,3), (1,4), (2,3), (3,4)
## concordant score is (1,2), (1,3), (1,4), (3,4)
## Harrell's c-index = 4/5 = 0.8
