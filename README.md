# Septicemia_Predictions
## Introduction  
Electronic Health Records (EHR) provide a rich source of data that can be leveraged to draw actionable insights that benefit doctors, clinicians and patients. However, understanding EHR data has been a challenging task in natural language processing (NLP) due to the nature of unstructured data types and complex sources. Additionally, high quality clinical phenotyping from EHR data typically requires time-intensive expert review. In this project, we propose to implement an semi-supervised NLP model with the objectives of better understanding EHR data and deriving insights that can improve health outcomes without the need of a domain expert.
clinically significant, like subtypes stratified on survival time or length of stay in the hospital. Generally,
we can perform deep phenotyping of sepsis.
The goal of this project is to use language models to
predict the presence of a septicemia-related (aka sepsis-related) ICD9 code from the unstructured clinical
notes of ICU patients. Specifically, we tackled the following two questions: 1) can we predict the number
of septicemia-related ICD9 codes, if any, a patient has been assigned based on their clinical notes? This
analysis is significant because we can potentially ide