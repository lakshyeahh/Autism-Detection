Autism Detection Model

Overview
This project aims to develop a model for autism detection using a modified version of Simon's Game to assess specific parameters related to Sensory Perception, Attention to Detail, and Multitasking Abilities. These parameters are crucial in identifying traits associated with Autism Spectrum Disorder (ASD). The game provides metrics such as Average Reaction Time (in milliseconds) and Accuracy Rate (in percentage), which are mapped to the responses recorded from the child during gameplay.

Dataset Description
The model is trained on a dataset consisting of 17 data points, where responses to Autism Quotient (AQ) questions are labeled as either 0 (not close to autism) or 1 (close to autism). Specifically, questions AQ2, AQ4, AQ6, and AQ8 are identified as relevant to Sensory Perception, Attention to Detail, and Multitasking Abilities.

Game Implementation
The assessment game is based on Simon's Game, enhanced with multiple levels and features to measure reaction time and accuracy. The collected gameplay data is correlated with AQ parameters to predict the likelihood of autism traits.
![Screenshot 2024-07-09 000347](https://github.com/lakshyeahh/Autism-Detection/assets/121057440/bc4e7682-a7cc-4bee-8764-1d0c2366a38b)

Threshold Values
The following threshold values were identified from research and data analysis to classify responses:

AQ Parameter	Average Reaction Time (ms)	Accuracy Rate (%)	Classification
AQ2	2500	70	1 (Close to ASD) if below threshold values, otherwise 0
AQ4	2200	78	1 (Close to ASD) if below threshold values, otherwise 0
AQ6	2000	75	1 (Close to ASD) if below threshold values, otherwise 0
AQ8	1800	80	1 (Close to ASD) if below threshold values, otherwise 0
Usage
![Simon Game Metrics](https://github.com/lakshyeahh/Autism-Detection/assets/121057440/05bd65b0-01d4-4dac-92a0-367a2332aaeb)

To use the model:

Ensure the game is set up to record Average Reaction Time and Accuracy Rate.
Feed the recorded metrics into the model to obtain predictions for AQ parameters.

