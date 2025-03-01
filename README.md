# CS506 Project - Resume Analyzer

We aim to build a tool that evaluates resumes and provides data-driven insights on how well they align with specific job descriptions. Instead of directly predicting job offer likelihood, our tool will analyze hiring data to identify the most influential factors affecting hiring decisions. This will offer quantifiable, evidence-based feedback beyond what existing AI resume evaluators provide.

## Project description:

By using **Natural Language Processing (NLP), machine learning models, and statistical analysis**, the project aims to create an actionable and ethical tool that helps job seekers **optimize their resumes** while also addressing **potential biases in the hiring process.**

## Goals:
- Develop a resume analysis tool that evaluates how well an applicant aligns with specific job listings
- Predict job offer likelihood
- Analyze potential bias in hiring decisions
## Key Features and Innovations
- Resume Score & Factor Analysis
- Extract meaningful features from resumes and job descriptions using BERT embeddings.
- Provide a quantitative resume score based on key factors like skills match, experience, and education.
  - Offer percentile rankings based on hiring outcome data (e.g., "Your skill match is in the top 25% for this job").
## Hiring Outcome Analysis
- Analyze a dataset of real hiring outcomes to determine which resume factors influence success.
- Use SHAP values and feature importance rankings to provide actionable insights.
- Example insight: "Resumes with X certification have a 30% higher chance of getting an interview for software engineering roles."
## Data Collection Strategy
- Resumes: Scrape public resume datasets (e.g., Kaggle, Resume.io, OpenResume) and collect voluntary submissions from students/professionals.
- Job Descriptions: Scrape job postings from LinkedIn, Indeed, Glassdoor, and Handshake or use job board APIs.
- Hiring Outcomes:
  - Collect hiring data via surveys of students/professionals (e.g., job applications, interview outcomes, offers).
  - Explore collaborations with career services to access anonymized hiring data.
  - Utilize existing HR datasets or research papers on hiring trends.

## Expected Impact
Unlike existing AI resume tools that only provide text-based feedback, our tool will offer data-backed insights on hiring success factors. By analyzing real-world hiring outcomes, we can provide more transparent, actionable recommendations that go beyond generic AI-generated responses.
This approach makes our project uniquely valuable by focusing on data-driven insights rather than just text-based resume feedback.
  
## Data:
- Resumes from public resume library/ database (e.g., Kaggle, Resume.io, OpenResume)
  - Method: Scraping public resume datasets or collecting resumes from willing participants (e.g., students, professionals)
- Job descriptions from job websites (e.g. LinkedIn, Indeed, Glassdoor, Handshake)
  - Method: Scraping job descriptions or using job board APIs
- Dataset that includes hiring outcomes (e.g., research papers, HR datasets, or self-collected surveys)
  - Method: Survey students/professionals on their job applications and outcomes  

## Data Model:
- BERT embedding to extract meaningful text features from resumes and job descriptions
- Logistic regression (job offer prediction to classify resumes as “likely to get an offer” vs. “unlikely)
## Data Visualization: 
- Radar chart  to visualize strengths and weaknesses of resumes based on key metrics such as skill match, experience, education, etc.
- Scatter plots to show feature importance vs. job offer probability
## Testing: 
- Unit test to verify correct feature extraction
- Dataset split, 20% for testing and 80% for training
- Use past records of resumes, job descriptions, and hiring outcomes to train data

