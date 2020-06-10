This folder contains code for deteting fraud in credit card transactions using auto-Encoders

Data :
Data is highly imbalanced with ratio of normal to fraud class of 99.83: 0.17

Auto-encoder has been trained only on identifying pattern for normal class. Once model has been trained, idea is to check it for fraud class, and it's reconstruction error should be high since it's pattern should be different from the normal class.


