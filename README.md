# Lead-Score-Case-Study
X Education Lead Conversion Model

Welcome to the X Education Lead Conversion Model repository. This repository contains all the necessary files and documentation for the logistic regression model developed to predict the probability of lead conversion for X Education, an online education company.

Repository Structure

- `model.py`: Python file containing the logistic regression model. This file is well-commented and includes detailed explanations of each step in the process.
- `questions_answers.docx`: Word document answering all the questions provided by the company.
- `presentation.pdf`: A PDF version of the presentation created to showcase the analysis and results to the chief data scientist. This presentation includes both technical and business insights.
- `summary_report.pdf`: A summary report detailing the model's development, evaluation, and business implications, converted to PDF from a Word document.

Project Overview

X Education is an online education company that offers courses to business professionals. The company advertises its courses on various websites and search engines like Google. After visiting the website, users can explore available courses, complete registration forms, or watch videos. Users who provide their phone number or email address by filling out a form are categorized as leads. The sales team then follows up with these leads through calls and emails. The goal is to develop a logistic regression model that predicts the probability of lead conversion to improve the company's lead conversion rate.

 Model Details

Objective
To build a logistic regression model to predict the probability of a lead converting to a customer, with an approximate lead conversion rate target of 80%.

Dataset
The dataset consists of around 9000 data points with various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. The target variable is 'Converted' (1 if converted, 0 if not).

Key Features
- `Lead Source_Welingak Website`
- `Current Occupation_Working Professional`
- `Lead Source_Reference`

Performance Metrics
The model's performance was evaluated using sensitivity-specificity and Precision-Recall metrics. The optimal cutoff was determined based on sensitivity-specificity. The conversion rate achieved by the final model is approximately 80.4329% on the test data, closely matching the 80.1876% on the train data, indicating a robust model.

Business Implications
The model is designed to align with the company's future requirements, providing a scalable solution to enhance lead conversion rates. By focusing on key features that drive conversions, the model helps the sales team prioritize high-potential leads, thereby improving efficiency and effectiveness.

Files Description

`model.py`
This Python file contains the entire code for the logistic regression model, including:
- Data preprocessing steps (handling missing values, encoding categorical variables)
- Feature selection
- Model training and validation
- Performance evaluation
The file is thoroughly commented to provide clarity on each step and ensure the code is easily understandable.

`questions_answers.docx`
This Word document addresses all the specific questions posed by the company, providing detailed responses based on the model's development and findings.

`presentation.pdf`
The presentation highlights the key aspects of the analysis, including:
- Project objective
- Data overview
- Methodology
- Model performance
- Business implications
The presentation is designed to be concise and clear, aimed at both technical and business audiences.

 `summary_report.pdf`
This summary report provides an in-depth overview of the project, covering:
- Introduction
- Data description
- Model building process
- Evaluation metrics
- Conclusion
The report is structured to offer a comprehensive understanding of the project from start to finish.


Conclusion

This logistic regression model serves as a strategic tool for X Education to enhance its lead conversion process. By leveraging key features and achieving a high conversion rate, the model offers significant business value in optimizing sales efforts and improving overall efficiency.

Thank you for using the X Education Lead Conversion Model repository!

