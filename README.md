# IBM Edunet Internship: AI & Cloud – Predictive Maintenance of Industrial Machinery

This repository documents my 4‑week IBM SkillsBuild internship (via Edunet Foundation) and the final project I completed using IBM watsonx.ai Studio.

## Internship Overview

- Program: IBM SkillsBuild 4‑Weeks Internship on AI & Cloud Technologies  
- Organizer: Edunet Foundation in collaboration with IBM SkillsBuild  
- Duration: 15 July 2025 – 7 August 2025  

### Internship Benefits
- Access to IBM SkillsBuild e‑learning with curated technical and professional courses
- Project‑based learning with mentor guidance
- Masterclasses by Subject Matter Experts
- Real‑world problem solving and portfolio project
- Certification from IBM SkillsBuild and Edunet Foundation upon successful completion

### Weekly Structure and Learning Plan

| Week | Day | Topic/Activity |
|------|-----|----------------|
| **Week 1** | Day 1 | Internship Orientation (virtual) |
|  | Day 2 | Registration in IBM |
|  | Day 3 | Cloud Computing |
|  | Day 4 | Artificial Intelligence |
| **Week 2** | Day 1 | Data Analytics |
|  | Day 2 | Data Analytics – Hands On |
|  | Day 3 | Data Analytics Cloud EDA |
| **Week 3** | Day 1 | Chatbot – AI |
|  | Day 2 | Cloud Experiment on Chatbot |
|  | Day 3 | ML Problem Statements walkthrough |
| **Week 4** | Day 1 | AI & ML experiments in Cloud |
|  | Day 2 | AutoAI Experiment in IBM Cloud |
|  | Day 3 | Final Project Evaluation & Submission |

***

## Certificates

Credentials earned during the internship:

1. Getting Started with Artificial Intelligence – IBM SkillsBuild  
   Issued: Jul 19, 2025
   <img width="1335" height="983" alt="AI" src="https://github.com/user-attachments/assets/75d96d39-e6bb-4d26-a973-e32c2ab04f5f" />
   
3. Journey to Cloud: Envisioning Your Solution – IBM SkillsBuild  
   Issued: Jul 20, 2025
   <img width="1340" height="985" alt="Cloud" src="https://github.com/user-attachments/assets/c38c99a3-d178-4325-a4f7-836d77e60f87" />
   
4. Lab: Retrieval Augmented Generation with LangChain – IBM SkillsBuild  
   Completion date: Jul 24, 2025 (20 mins)
   <img width="1594" height="982" alt="RAG" src="https://github.com/user-attachments/assets/687a2f33-e692-4390-bf22-89fadfa92f57" />

***

## Final Project: Predictive Maintenance of Industrial Machinery

The project demonstrates how AI can predict equipment failures in advance, enabling proactive maintenance and reduced downtime.

### Objective
Build and deploy a model that classifies machine failure types from sensor data to alert maintenance teams before breakdowns occur.

### Dataset
- Source: Kaggle – Predictive Maintenance Classification  
  (Dataset by shivamb: machine predictive maintenance classification)

### Tools and Platform
- IBM watsonx.ai Studio (AutoAI)
- IBM Cloud Deployment Spaces for model deployment
- Python/Jupyter for exploration and documentation

### Workflow

1. Data Upload  
   Imported the sensor dataset into IBM watsonx.ai Studio.

2. AutoAI Experiment  
   Automated data cleaning, feature engineering, and model selection.  
   Multiple pipelines generated and ranked by cross‑validation performance.

3. Best Model  
   Algorithm: Snap Decision Tree Classifier  
   Cross‑validation accuracy: ~0.978  
   Holdout accuracy: ~0.981  
   Evaluations included ROC curves per class, confusion matrix, precision‑recall, and threshold analysis.

4. Deployment  
   Promoted the best pipeline to a deployment space and exposed it as an online endpoint for real‑time predictions.

5. Predictions  
   Multiclass outputs include: Power Failure, Overstrain Failure, No Failure, etc., with high confidence scores.

### Jupyter Notebook
- Final project notebook: [https://github.com/Omii1908/Edunet-IBM-Internship-Project/blob/main/Predictive%20Maintenance%20of%20Industrial%20Machinery%20Model.ipynb]

Replace the above path with your actual notebook location if different.

### Final Project Screenshots

- AutoAI Pipeline Summary / Leaderboard Detail
  <img width="1920" height="1200" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/b222342d-f2f5-446a-afb2-7852d849113a" />
  
- Model Training Status and Metrics
  <img width="1920" height="1200" alt="Screenshot (45)" src="https://github.com/user-attachments/assets/e49b4a3f-3701-4f73-abfc-05a7d228c03f" /> 
  
- Evaluation: ROC Curves and Confusion Matrix  
  <img width="1920" height="1200" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/ae8d3cc3-640c-44eb-b816-6c7538632f13" />
  <img width="1920" height="1200" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/ca71720d-92a5-4526-bd77-485e7f6ff746" />

- Deployment Space and Online Endpoint  
  <img width="1920" height="1200" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/55e7aa28-035a-4bbd-b56b-a22cc3a3413b" />

- Deployed Endpoint Prediction Output  
  <img width="1920" height="1200" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/0eaece01-1a21-47aa-8e25-f04622eea770" />

***

## Results

- Achieved strong multiclass classification performance:  
  Cross‑validation accuracy: ~97.8%  
  Holdout accuracy: ~98.1%  
- Clear separation in ROC curves for key failure modes  
- Successful cloud deployment enabling live inference with confidence scores

***

## Outcome of the Internship

- Completed all scheduled sessions, IBM registrations, and learning plan requirements  
- Built, evaluated, and deployed a production‑style ML model using IBM watsonx.ai and IBM Cloud  
- Gained practical skills in cloud AutoML, deployment, and interpreting multiclass metrics  
- Earned certifications from IBM SkillsBuild and Edunet Foundation upon successful project submission and presentation

***

## How to Reproduce

1. Download the Kaggle dataset and upload it to IBM watsonx.ai Studio  
2. Create an AutoAI classification experiment and run with default safeguards  
3. Select the top pipeline, promote to a Deployment Space, and deploy as an online endpoint  
4. Optionally, open the Jupyter notebook and follow the steps to document/validate results  
5. Use the deployed scoring URL to send JSON payloads for predictions

***

## Acknowledgements

Thanks to IBM SkillsBuild, Edunet Foundation, and mentors for guidance throughout the internship, and to the Kaggle community for the dataset used in this project.

***
