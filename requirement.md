# Assignment 2

## Yash Patel – 9049539  
SENG8091 Software Engineering Principles  

---

## Scenario
Your client is an AI developer who uses publicly available data to train their AI. They have approached you to help them overcome some of their difficulties.

The client uses a technique called web scraping to generate their training data. 

You have had a few meetings with the client. At this point, you are quite confident that you understand the challenge.

---

## Functional Requirements

### 1. Categorization of Training Questions and Answers
- **Assumption**: Developers require a structured way to categorize training questions and answers.
- **Validation**: Conduct surveys and interviews with developers to confirm categorization methods align with expectations.

### 2. Interface for Reviewing Categorized Training Questions
- **Assumption**: A user-friendly interface is required to allow developers to efficiently manage training questions.
- **Validation**: Perform UI testing to ensure smooth user interaction.

### 3. Bias Detection Algorithm
- **Assumption**: The system must support both predefined and customizable bias detection criteria.
- **Validation**: Check the datasets that already exist against the ones that have biases marked and use developer feedback to judge the accuracy.

### 4. Manual Review of Flagged Data
- **Assumption**: Human monitoring is necessary for AI-generated bias detection to be as accurate as possible.
- **Validation**: Install an audit function that tracks manual modifications to biases that have been detected and examines user modifications over time.

### 5. Report Generation on Data Distribution and Biases
- **Assumption**: Developers require visual analytics to assess the fairness of datasets.
- **Validation**: Generate example reports and ask developers for input on their efficacy and clarity.

### 6. Exporting Structured Training Datasets
- **Assumption**: Standard AI formats are required for easy integration into AI models.
- **Validation**: Verify data format compatibility by conducting integration tests with current AI models.

### 7. Role-Based Access Controls
- **Assumption**: Different team members will have varying levels of responsibility for managing training data.
- **Validation**: Model workflows with multiple users and make sure role-based limitations perform as intended.

### 8. Search and Filtering Feature
- **Assumption**: Developers need efficient tools for searching and retrieving relevant training data.
- **Validation**: Conduct performance tests on search speed and accuracy for various dataset sizes.

### 9. Scheduled and Real-Time Web Scraping
- **Assumption**: Performance of AI models is improved by regular updates to training datasets.
- **Validation**: Evaluate the efficacy of data retrieval by running tests on various websites.

---
