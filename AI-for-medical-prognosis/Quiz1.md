## 1. Which of the following is not an example of a clinical application of a prognostic model?
- Detecting atrial fibrillation automatically using a EKG

## 2. Recall the MELD score from the lesson. What is the output for a person with
Creatinine = 0.8 mg/dL,

Bilirubin total = 1.5 mg/dL,

INR = 1.3

Remember that the final score is multiplied by 10.

Please use natural logarithm instead of base 10 log.

You can also watch the video "Liver Disease Mortality" to review the calculation of the MELD score.
- 8.76
A. (ln(0.8)*0.957 + ln(1.5)*0.378 + ln(1.3)*1.120+0.643)*10

## 3. You’ve fit a linear model with no interaction terms, and which include Age (in years) as an input feature of the model. Also, you don't multiply the sum product by any scaling number (unlike the MELD score, for instance).
- 0.8

## 4. A linear risk model for the risk of heart attack has three inputs: Age, Systolic Blood Pressure (BP), and the interaction term between Age and Systolic Blood Pressure. The coefficients for Age, BP, and the interaction term are 0.1, 0.3, and 0.5.
Can you determine how an increase in blood pressure is affected by an increase in age?
- As you get older, the same increase in blood pressure leads to LARGER change in your risk of heart attack.

## 5. If a feature xx has range 0 to \infty∞, then what is the range of \ln(x)ln(x)?
- [-∞, + ∞]

## 6. True or False: If a > b, then ln(a) > ln(b).
- True 

## 7. Which assignment of risk would make the following pair concordant?
- [0.5 , 0.83]

## 8. What is the C-index for the following set of predictions?
- 0.75
A. 3/4


## 9. What is the C-index for a model which always outputs 0.6 for any patient regardless of their health outcome?
- 0.5

## 10. Model 1 has a c-index of 0.7 and Model 2 has a c-index of 0.6. Which is more accurate using a threshold of 0.5 for the risk score?
- There is not enough to say.

In other words, if the risk score is 0.5 or higher, predict that the patient will have the disease in the future. If the risk score is < 0.5, predict that the patient will not have the disease.
