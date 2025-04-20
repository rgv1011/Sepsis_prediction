**Introduction**

Sepsis is a life-threatening condition of a patient which is caused by the human body's extreme response to infection, leading to tissue damage, organ failure and even death. It is one of the leading causes of death in Intensive Care Units (ICUs) worldwide, especially when not detected in the initial period. Early recognition and timely intervention are critical in improving patient outcomes.
Traditionally, sepsis diagnosis relies on manual clinical scoring systems like SIRS (Systemic Inflammatory Response Syndrome) and SOFA (Sequential Organ Failure Assessment). These systems, although helpful, are not always effective in real-time environments and often miss subtle warning signs. The increasing availability of electronic health records (EHRs) and ICU monitoring systems provides a unique opportunity to harness machine learning and deep learning to automate and enhance early sepsis detection.

**Problem Statement**

The objective of this project is to develop a machine learning model that can accurately predict the likelihood of sepsis onset in ICU patients based on a wide range of physiological parameters collected over time. Early prediction of sepsis could drastically reduce mortality rates by enabling clinicians to administer timely interventions. The aim includes:
•	Develop a predictive model using an LSTM-based deep learning network to handle time-series ICU data.
•	Use key patient vitals and lab test results as input features.
•	Train the model on publicly available sepsis datasets.
•	Deploy the model with an interactive input interface for live testing.

**Research Paper Reference**

Title: "A Machine Learning Approach to Predict Sepsis Using Vital Signs in ICU Patients"
Source: PhysioNet 2019 Challenge – Early Prediction of Sepsis from Clinical Data
Authors: Reyna M. A., Josef Clifford G., et al.

The dataset comprises hourly vital signs and lab measurements of ICU patients, with a binary label indicating the presence or absence of sepsis. The LSTM model is chosen for its effectiveness in learning patterns from sequential medical time-series data, making it highly suitable for early sepsis detection.
