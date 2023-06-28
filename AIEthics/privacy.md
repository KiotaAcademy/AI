# PRIVACY

Data is the heart of AI. Because AI ingests so much data to learn, identify patterns, and make predictions or recommendations, it must prioritize and safeguard the privacy of all of the data it comes into contact with.

Personal information (PI)  is any information relating to an identified or identifiable individual, like a name or postal code.

Sensitive personal information (SPI) is information that, if compromised, could be misused to significantly harm or inconvenience an individual, like a bank account number or birth date

## MEMBERSHIP INFERENCE ATTACK

n a membership inference attack, an attacker tries to determine whether a specific individual was part of the training data set.

there are many privacy controls that can be applied to fortify AI against potential breaches of personal or sensitive data:

1. Model Anonymization
2. Differential privacy

that's during model training, after model training we can:

1. Data minimization

## Model Anonymization

The goal of model anonymization is to anonymize the training data with minimal accuracy loss. After all, if the model is trained on anonymous data, then the model itself is anonymous and there is little risk to any personal data used during training.

## Differential privacy

In differential privacy, random noise is added during model training to reduce the impact of any single individual on the model’s outcomes and to give a guarantee that an individual in the training data set could not be identified.

## Data minimization

Data minimization means that only data that is needed is being collected. This control helps prevent privacy breaches by limiting the amount of personal data that is collected in the first place and by ensuring that collected data is only as granular as needed. For example, data minimization might mean that you collect only an individual’s zip code instead of their full address, or only their year of birth instead of their full birth date.

