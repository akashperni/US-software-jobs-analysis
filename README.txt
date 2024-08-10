# US Software Engineering Job's Analysis

**Team Members:**
- Akash Perni
- Sai Ganesh Pendela
- Samba Sivesh Kurra
- Venkata Phani Aditya Nutalapati

**Institution:**  
University of Maryland, College Park

---

## Overview
This project explores the US Software Engineering job market by leveraging machine learning algorithms to classify job salaries based on a variety of features. The dataset includes over 58,000 job postings with detailed attributes such as job title, company, location, and more. The primary objective is to predict salary ranges using advanced machine learning models, providing valuable insights for job seekers and employers.

## Dataset
The dataset was sourced from Kaggle and consists of 58,433 rows and 29 columns. Key features include:
- **Title:** The job title associated with the posting.
- **Company:** The hiring company.
- **Salary:** The expected or offered salary.
- **Rating:** The company's rating, reflecting its reputation.
- **Location:** The job location.
- **Snippet:** A brief description of the job.

## Methodology
### Data Preprocessing
- **Handling Missing Values:** Missing salaries were filled using the mean salary for the respective job title, company, and location.
- **Encoding:** Categorical variables like job title and company were encoded using Word2Vec.
- **Feature Engineering:** Introduced new features such as 'years of experience' and 'relative time' of job postings.

### Model Building
The following machine learning models were built using Scikit-Learn:
- **Logistic Regression**
- **Decision Tree**
- **K-Nearest Neighbors (KNN)**
- **Random Forest**

### Evaluation Metrics
Models were evaluated based on:
- **Accuracy**
- **Precision**
- **Recall**
- **Cross-Validation Scores**

## Key Findings
- **Top Hiring Companies:** Companies like Capital One, Indeed, and Liberty Mutual Insurance are top employers offering jobs with visa sponsorship.
- **High-Demand Roles:** Software Engineer, Senior Software Engineer, and DevOps are the most in-demand job roles.
- **Geographical Trends:** California has the highest number of job postings, with remote jobs leading in visa sponsorships.

## Results
- **Random Forest:** Achieved the highest accuracy of 93.57%, making it the most reliable model for salary classification.
- **Decision Tree & KNN:** Both models performed well with accuracy rates around 90%, though with varying precision and recall values.
- **Logistic Regression:** Had the lowest performance with an accuracy of 69%.

## Conclusion
The Random Forest model stood out with its superior performance, indicating the effectiveness of ensemble learning for this type of classification task. The insights gained from this project can significantly aid both job seekers and employers in the software engineering industry.

## Future Work
- **Additional Features:** Incorporating more features could further improve model accuracy.
- **Dataset Updates:** Regular updates to the dataset would keep the models relevant with current trends.
- **Advanced Techniques:** Exploring deep learning models could uncover more complex patterns in the data.

---

## Installation and Usage

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/us-software-jobs-analysis.git
    ```

2. **Open the project folder in Google Drive and open the `IS_SDE_JOBS_PROJECT.ipynb` file in Google Colab.**

3. **Run all the cells** to execute the entire project, from data preprocessing to model evaluation.

---

## Acknowledgments
- Kaggle for providing the dataset.
- Scikit-Learn and other open-source libraries used in this project.


