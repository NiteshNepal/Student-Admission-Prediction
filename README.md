# Student-Admission-Prediction

**CONTENTS:**
1. The Problem Statement
2. Application Design
3. Pre-requisites
4. Python Implementation
5. Flask App
6. Final Result

**1. The Problem statement:**
The goal here is to find the chance of admission of a candidate based on his/her GRE Score (out of 340), TOEFL Score (out of 120), rating of the University (out of 5) in which he/she is trying to get admission,
Strength of the SOP (out of 5), strength of the Letter Of Recommendation (out of 5), CGPA (out of 10) and the research experience (0 or 1).

**2. Application Design:**
Once we have the data source fixed, the machine learning approach majorly consists of two pipelines:
• The Training Pipeline
The training pipeline includes data pre-processing, selecting the right algorithm for creating the machine learning model, checking the accuracy of the created model and then saving the model file. 
![Flow1](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/ac9619bf-2595-4f8c-a60d-d924f770765f)

![Flow2](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/cde3dcf0-af10-4df6-9902-1420247004d3)

3. Pre-requisites:
• Basic knowledge of flask framework.
• Any Python IDE installed.
• Basic understanding of HTML and CSS.

5. Python Implementation:
4.1 Importing the necessary Files
We’ll first import all the required libraries to proceed with our machine learning
model.
# necessary Import
![Necessary Import](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/2492b339-59e9-4b32-ab67-5b535b451bf4)

4.2 Reading the Data File
![Screenshot 2023-10-03 163606](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/d6ead65c-388b-4391-917c-eb48c1e84de4)

4.3 Data Preprocessing
![Screenshot 2023-10-03 193259](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/5d76994e-7117-44be-ba47-40068f668a46)
Checking for Null values and filling the NAN value.
![Screenshot 2023-10-03 193336](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/9b21c0ad-d0fc-447b-a433-bedf87c4d1ba)

4.4Scaling the Data into same scale.
![Screenshot 2023-10-03 193434](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/2360dc71-161d-450b-a432-7ced681ba019)

4.5 Splitting the data into train and test data.
![Screenshot 2023-10-03 193607](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/14b384c3-de72-41fd-8093-e9a43e7e9ec0)

4.6 Training the model
![Screenshot 2023-10-03 193635](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/bd74e440-1bbc-43a9-b72f-cce77b097ca0)

4.7 Prediction of the model with accuracy score.
![Screenshot 2023-10-03 193759](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/20e5c8d6-433b-4fda-ab2a-8129d4e25cb5)


5.Flask App:
As we’ll expose the created model as a web API to be consumed by the client/client APIs, we’d do it using the flask framework.
The flow of our flask app will be:
![Flask](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/e4457d5f-28b8-41f9-85fe-107317e5a027)


6. Final Result
   ![Home screen](https://github.com/NiteshNepal/Student-Admission-Prediction/assets/110449990/29182c35-8fa1-4bbc-b3cd-62cbdc27d4fe)


