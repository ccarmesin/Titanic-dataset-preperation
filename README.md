![Titanic theme](https://image.brigitte.de/11048874/t/HU/v4/w960/r1.5/-/titanic-untergang.jpg)
# Titanic-dataset-preperation
Just a simple script to convert the titanic dataset to a numerical dataset that can be used to train self learning algorithms.
Trying out first [Kaggle](https://www.kaggle.com/) dataset exploration.

# Credits

* [Dataset](https://www.kaggle.com/c/titanic)
* [README example](https://github.com/codelibra)

# Problem Overview
We need to predict for each testing data whether the person was able to survive or not based on the model learnt from training data.

## VARIABLE DESCRIPTIONS
1. survival        Survival (0 = No; 1 = Yes)
2. pclass          Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)
3. name            Name
4. sex             Sex
5. age             Age
6. sibsp           Number of Siblings/Spouses Aboard
7. parch           Number of Parents/Children Aboard
8. ticket          Ticket Number
9. fare            Passenger Fare
10. cabin           Cabin
11. embarked        Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)

## SPECIAL NOTES
1. Pclass is a proxy for socio-economic status (SES)
 1st ~ Upper; 2nd ~ Middle; 3rd ~ Lower

2. Age is in Years; Fractional if Age less than One (1)
 If the Age is Estimated, it is in the form xx.5

3. With respect to the family relation variables (i.e. sibsp and parch)
some relations were ignored.  The following are the definitions used
for sibsp and parch.

 Sibling:  Brother, Sister, Stepbrother, or Stepsister of Passenger Aboard Titanic
 Spouse:   Husband or Wife of Passenger Aboard Titanic (Mistresses and Fiances Ignored)
 Parent:   Mother or Father of Passenger Aboard Titanic
 Child:    Son, Daughter, Stepson, or Stepdaughter of Passenger Aboard Titanic

4. Other family relatives excluded from this study include cousins,
nephews/nieces, aunts/uncles, and in-laws.  

5. Some children travelled
only with a nanny, therefore parch=0 for them.  As well, some
travelled with very close friends or neighbors in a village, however,
the definitions do not support such relations.
