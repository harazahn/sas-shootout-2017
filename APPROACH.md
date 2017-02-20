# Overall modeling approach

## Modeling Task 1 - Conditions :fire:

Predicting "propensity of wildfire at any given time based on the current conditions at that same time."

**Classification**

Start with basic logistic regression and go from there.

## Modeling Task 2 - Causes :fire:

Produce a model that will predict the probability of potential causes of a wildfire by time and geography.

**Classification**
**Clustering?**
**NLP**

Will have to parse "Wildfire Narratives" file.
**Not** a binary classifier.
Are any fires labeled by cause? Will have to check wildfire_events and wildfire_narrative. If not, then unsupervised learning.

## Modeling Task 3 - Impacts :fire:

Build a model that predicts acres burned from the provided variables.

**Regression**
**NLP**

Based on cause, geography, weather before & after ignition, etc.
Get more info from wildfire_narrative.