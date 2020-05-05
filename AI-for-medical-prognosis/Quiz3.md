## 1. Let f(x)f(x) be the probability that a person with feature xx dies within 5 years.
## Let S_{x}(t)S x(t) be the survival function of a person with feature xx. Assume t is measured in years.
## Which of the following is true?
## A. f(x) = 1-S_x(5)

## 2. The survival function is always
## A. Decreasing

## 3. Which of the following is a difference between survival data and classification datasets?
## A. IN survival data the labels are amounts of time and in classification data the labels are binary.

## 4. Which of the following is an example of censoring?
## A. The patient withdraws from a study before having an event, and before the study ends.
## A. Death due to other, unrelated causes (such as an automobile accident)
## A. The patient withdraws from a study before having an event, and before the study ends.

## 5. Estimate P(T > 2 | T >= 2)P(T>2∣T>=2) from the following dataset:
## A. 3/4

## 6. Compute the probability of surviving up to 4 years S(4)S(4) given the following dataset using the Kaplan Meier estimate:
## A. 1/2
## How to answer: 
## S(4) = (1-P(T=2|T>=2))(1-P(T=3|T>=3))(1-P(T=4|T>=4))
##      = (1-1/4)(1-1/3)(1-0) = 3/4*2/3 = 1/2

## 7. Compute S(5) given the following dataset using the Kaplan Meier estimate (note, it's the same dataset as in the previous question).
## A. 0
## S(5) = S(4) * (1 - P(T=5|T>=5)) = S(4) * (1 - 1) = 0

## 8. True or False: If t is larger than the longest survival time recorded in the dataset, then S(t) = 0S(t)=0 according to the Kaplan-Meier estimate.
## A. False
