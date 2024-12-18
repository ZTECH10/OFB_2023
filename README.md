# Ottawa Food Bank

## Research Questions
1. What is the relationship between food security status and health/demographics/needs in our sample?

  - Neighbour Survey : neighbour_survey_clean-2024-06-14.csv
    -   'NaN' value here means that the respondent did not select an option for a boolean column or skipped the question for a factor column.
    -   if the respondent did not select an option for a boolean column, 'NaN' is treated as False.
    -   If the respondent skipped the question for a factor / text column, then NaN is treated as 'Prefer not to answer' This means 'NaN' will have the same categorical code as 'Prefer not to' answer column
2. Considering the stated needs of people accessing food programs, do agencies/the network have the capacity to meet those needs?

## Data Details
In this repository, you will find two password-protected ZIP files containing survey data:

- **Hunger Count**
  - Number of Records: 85
  - Number of Fields: 49
  - Files: "Hunger Count.docx" (questionnaire), "Hunger Count.csv" (responses, UTF-8 encoded)

- **Neighbour Survey**    
  - Number of Records: 4086
  - Number of Fields: 136
  - Files: "Neighbour Survey.docx" (questionnaire), "Neighbour Survey.csv" (responses, UTF-8 encoded)
  -  Description:  Contains information on the needs of people accessing food programs, including food security experiences, financial status, barriers to accessing food programs, non-food services, special food needs, as well as demographics, health conditions, visitor traffic, and comments and feedback.  
    
      
      
      ### Fields Description
      
      #### Needs of People Accessing Food Programs
      
      | Questions                                    | Description                                                      |
      |----------------------------------------------|------------------------------------------------------------------|
      | `q002` through `q008`                        | Food Security Experience and Financial Status-Income              |
      | `q014a` through `q014h`                      | Food Programs Access Barriers                                    |
      | `q017a` through `q018`                       | Food Programs ‘Non-Food’ Services                                |
      | `q023a` through `q024i`                      | Food Programs Special/Unique Food Needs                          |
      
      #### Demographics
      
      | Questions                                    | Description                                                      |
      |----------------------------------------------|------------------------------------------------------------------|
      | `q025`                                       | Age                                                              |
      | `q026` through `q032`                        | Personal Household Questions                                     |
      | `q033a` through `q034`                       | Education Level                                                  |
      | `q035a` through `q035b`                      | Status in Canada                                                 |
      | `q036a` through `q036b`                      | Gender                                                           |
      | `q037`                                       | Time in Canada                                                   |
      | `q038a` through `q038k`                      | Ethnic Background                                                |
      | `q040a` through `q040b`                      | Housing Situation                                                |
      | `q041a` through `q041u`                      | Current Employment                                               |
      
      #### Health
      
      | Questions                                    | Description                                                      |
      |----------------------------------------------|------------------------------------------------------------------|
      | `q021a` through `q021f`                      | Health Conditions                                                |
      | `q039a` through `q039i`                      | Additional Health Conditions                                     |
      | `q019` through `q020`                        | Exercise Habits                                                  |
      | `q022`                                       | Pregnancy                                                        |
      
      #### Visitor Traffic
      
      | Questions                                    | Description                                                      |
      |----------------------------------------------|------------------------------------------------------------------|
      | `q009` through `q013`                        | Food Bank / Food Programs Visits                                 |
      | `q015` through `q016f`                       | Duration and Mode of Transportation to Food Programs             |
      
      #### Comments
      
      | Questions                                    | Description                                                      |
      |----------------------------------------------|------------------------------------------------------------------|
      | `q042`                                       | Comments and Feedback                                            |
      





## Analysis Methodology

<img width="821" alt="Screen Shot 2024-08-13 at 2 51 52 PM" src="https://github.com/user-attachments/assets/ea457f55-0e50-49f8-ac54-4ee075edb522">
<img width="821" alt="Screen Shot 2024-08-13 at 2 52 11 PM" src="https://github.com/user-attachments/assets/12943ca4-db39-43a5-8d98-b6c9ac6bd350">
<img width="821" alt="Screen Shot 2024-08-13 at 2 53 51 PM" src="https://github.com/user-attachments/assets/4f1c6c9d-1d50-4420-bdfb-64d44ddf043f">
<img width="821" alt="Screen Shot 2024-08-13 at 2 54 09 PM" src="https://github.com/user-attachments/assets/de492420-7d4a-4bc7-a281-4cc172029dfe">
<img width="821" alt="Screen Shot 2024-08-13 at 2 54 21 PM" src="https://github.com/user-attachments/assets/ebe66839-f3f4-4e4c-9616-b5c5ac42dceb">
<img width="821" alt="Screen Shot 2024-08-13 at 2 54 33 PM" src="https://github.com/user-attachments/assets/22cd03ff-e1c0-4ae0-8b5d-dbab18e7396e">

  
## Purpose
This repository aims to facilitate research and analysis related to food security, health demographics, and community needs as observed through surveys conducted by the Ottawa Food Bank. Researchers, analysts, and volunteers interested in understanding and addressing food insecurity issues are encouraged to explore and contribute to this repository.

Thank you for your interest in the Ottawa Food Bank repository. Your contributions can help make a difference in understanding and addressing food insecurity issues in our community.

## How to Contribute

1. **Fork the Repository**
   - Start by forking the [main repository](https://github.com/Data-For-Good-Ottawa/open-datasets-api/discussions/2) to your GitHub account. This creates a personal copy of the repository where you can make changes.

2. **Work on Your Project**
   - Clone your forked repository to your local machine and begin working on your project. You can analyze the data, create visualizations, or develop models based on the research questions and data provided.

3. **Document Your Work**
   - Ensure that you document your process, findings, and any code changes. This helps maintain transparency and allows others to understand your contributions.

4. **Push Changes to Your Fork**
   - Once you have completed your project, push all your changes back to your forked repository on GitHub.

5. **Submit a Pull Request**
   - Go to the original main repository and submit a pull request from your fork. In your pull request, provide a clear description of your work, including what you have added or changed and how it addresses the research questions or adds value to the project.

6. **Review Process**
   - The repository maintainers will review your pull request, provide feedback if necessary, and merge it into the main repository. This collaborative process ensures that all contributions are vetted and integrated seamlessly.

7. **Track Contributions**
   - You can track the status of your pull request and any discussions or reviews in the "Pull Requests" section of the main repository. Stay engaged and respond to any questions or feedback from the maintainers.

By following these steps, you help ensure that contributions are organized, trackable, and integrated effectively. Your participation can significantly aid in the research and understanding of food security issues in our community.

Thank you for contributing to the Ottawa Food Bank repository. Together, we can make a meaningful impact on addressing food insecurity.
