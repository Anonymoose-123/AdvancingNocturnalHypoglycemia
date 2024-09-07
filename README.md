Repository for the paper "Advancing Beyond Glucose-Only Methods for Predicting Overnight Nocturnal Hypoglycemia in Children with Diabetes".
Below are the 6 feature sets compared in the "Advancing Beyond Glucose-Only Methods for Predicting Overnight Nocturnal Hypoglycemia in Children with Diabetes" paper.

# 1. All Features
**Glucose-related:**
Glucose, hypoglycemia event, glucose linear regression slope, glucose evening low and peak, daily glucose minimum, standard deviation of glucose differences, coefficient of glucose variation

**Heart-related:**
Heart rate, heart rate variability, heart rate evening low and peak, heart rate variability evening low and peak, heart rate variability minimum

**Physical Activity:**
Motion activity, activity classification, number of steps, perfusion index, respiration rate, energy, activity score, wellness index evening low and peak

**Temperature & Pressure:**
Core temperature, temperature local, temperature object, barometer pressure

**Additional Biometrics:**
Blood pulse wave, GSR electrode, gender, age, weight, height, BMI, basal percentage, basal total

**Insulin & Diabetes Data:**
Glycated hemoglobin (HbA1c) reading, total daily insulin dose, max daily insulin fast, max daily insulin slow, total daily fast insulin, total daily slow insulin

**Others:**
Health score, training effect score, richness score

# 2. Paper-Based Features
**Core Features:**
Activity classification, blood pulse wave, core temperature, GSR electrode, heart rate, heart rate variability, motion activity, number of steps, perfusion index, respiration rate

**Demographics:**
Gender, age, weight, height, BMI

**Insulin & Diabetes Data:**
Basal percentage, basal total, glycated hemoglobin (HbA1c) reading, total daily insulin dose, max daily insulin fast, max daily insulin slow, total daily fast insulin, total daily slow insulin

**Glucose Metrics:**
Glucose linear regression slope, glucose evening low and peak, daily glucose minimum, standard deviation of glucose differences, coefficient of glucose variation

# 3. Reduced Selection
**Core Features:**
Glucose, hypoglycemia flag, activity classification, blood pulse wave, core temperature, GSR electrode, heart rate, heart rate variability, motion activity, number of steps, perfusion index, respiration rate

**Insulin & Demographics:**
Max daily insulin fast, max daily insulin slow, total daily fast insulin, total daily slow insulin, gender, age, weight, height, BMI, basal percentage, basal total, glycated hemoglobin (HbA1c) reading, total daily insulin dose

**Glucose Metrics:**
Glucose linear regression slope, glucose evening low and peak, daily glucose minimum, standard deviation of glucose differences, coefficient of glucose variation

# 4. Everion Global Only
**Glucose-related:**
Glucose, hypoglycemia flag

**Insulin & Diabetes Data:**
Max insulin fast, max insulin slow, total insulin fast, total insulin slow, glycated hemoglobin (HbA1c) reading, total daily insulin dose

**Demographics:**
Gender, age, weight, height, BMI, basal percentage, basal total

**Heart-related:**
Heart rate variability evening low and peak, heart rate variability minimum

# 5. No Calculated Globals
**Core Features:**
Glucose, hypoglycemia flag, heart rate, perfusion index, motion activity, activity classification, heart rate variability, respiration rate, energy, core temperature, temperature local, barometer pressure, GSR electrode, health score, training effect score, activity score, richness score, blood pulse wave, temperature object, temperature barometer

**Insulin-related:**
Max insulin fast, max insulin slow, total insulin fast, total insulin slow

# 6. Personalized Glucose
**Glucose-related:**
Glucose personalized, hypoglycemia events, glucose linear regression slope, glucose evening low and peak, daily glucose minimum, standard deviation of glucose differences, coefficient of glucose variation

**Heart-related:**
Heart rate, heart rate variability

**Insulin-related:**
Max insulin fast, max insulin slow, total insulin fast, total insulin slow
