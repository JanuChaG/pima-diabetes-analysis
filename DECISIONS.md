# Project Decisions Log

## 1. Assumptions
- Key predictors selected: Glucose, BMI, Age, and Pregnancies, based on their established relevance in diabetes risk.  
- Assumed that the dataset, once cleaned, provides a reliable basis for modeling.  
- Assumed that findings can be generalized to similar populations, though external validation would strengthen this claim.  

## 2. Model Choices
- Logistic Regression was adopted as a baseline model due to its interpretability and simplicity.  
- Random Forest was introduced to capture non‑linear relationships and improve predictive strength.  
- Models were compared using Accuracy, Precision, Recall, and F1‑score to ensure balanced evaluation.  

**Results (from modeling notebook):**
- Logistic Regression: Accuracy = 0.701, Precision = 0.58, Recall = 0.537, F1 = 0.558.  
- Random Forest: Accuracy = 0.714, Precision = 0.60, Recall = 0.556, F1 = 0.577.  
- Random Forest achieved slightly higher overall performance, while Logistic Regression remained more transparent and easier to interpret.  

## 3. Challenges
- Recall values remained moderate, highlighting the difficulty of identifying all positive cases.  
- Trade‑off between interpretability (Logistic Regression) and performance (Random Forest).  
- Ensuring reproducibility required careful attention to requirements files and notebook structure.  

## 4. Documentation & Workflow
- GitHub repository serves as the central platform for project management.  
- Structured commits are maintained to reflect clear milestones.  
- Requirements.txt ensures reproducibility across environments.  
- Jupyter notebooks are used directly for clarity and transparency.  
- Note: For larger projects, code would typically be modularized into `.py` files (e.g., preprocessing, modeling, utilities). In this submission, notebooks are retained to prioritise readability and examiner accessibility.  
- README.md provides an overview, workflow, and results for examiners and collaborators.  
  

