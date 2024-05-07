# MLOps---NLP---Case-Study-BeHealthy
This project creates a CRF model for a custom NER (Named Entity Recognition) task. The dataset is a collection of sentences from the patient's clinical notes.

# Problem Statement
‘BeHealthy’ has a web platform that allows doctors to list their services and manage patient interactions and provides services for patients such as booking interactions with doctors and ordering medicines online. Here, doctors can easily organize appointments, track past medical records and provide e-prescriptions. The requirement is to build a custom NER to get the list of diseases and their treatment from the dataset.

# Dataset
The dataset consist of four files containing words in line separate format:

- train_sent
- test_sent
- train_label
- test_label


# Q1. System design: Based on the above information, describe the KPI that the business should track.
# Q2. System Design: Your company has decided to build an MLOps system. What advantages would you get by opting to build an MLOps system? 
# Q3. System design: You must create an ML system that has the features of a complete production stack, from experiment tracking to automated model deployment and monitoring. For the given problem, create an ML system design (diagram). 

The MLOps tools that you want to use are up to your judgement. You can use open-source tools, managed service tools or a hybrid. 
You can use draw.io or any other convenient tool to create the architecture. You can refer to the module on “Designing Machine Learning Systems” for your understanding how to create an MLOps Architecture. 
You can upload the design/diagram as an image in the PDF.
 
# Q4. System design: After creating the architecture, please specify your reasons for choosing the specific tools you chose for the use case.
# Q5. Workflow of the solution: 
You must specify the steps to be taken to build such a system end to end. 
The steps should mention the tools used in each component and how they are connected with one another to solve the problem. 
Broadly, the workflow should include the following. Be more comprehensive of each step that is involved here.

- Data and model experimentation
- Automation of data pipeline
- Automation of the training pipeline
- Automation of inference pipeline
- Continuous monitoring pipeline
 
The workflow should ALSO explain the actions to be taken under the following conditions. 
After you deployed the model, you noticed that there was a sudden increase in the drift due to a shift in data.

- What component/pipeline will be triggered if there is any drift detected? What if the drift detected is beyond an acceptable threshold?
- What component/pipeline will be triggered if you have additional annotated data?
- How will you ensure the new data you are getting is in the correct format that the inference pipeline takes?

# Contact
Created by [@GowthamiGanga] - feel free to contact me!
