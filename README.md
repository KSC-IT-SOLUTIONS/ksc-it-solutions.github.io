Coding Standards Document

1. **Introduction : -**
This document outlines the coding standards followed in our development practices, covering various aspects of code organization, naming conventions, documentation, and version control strategies. Adhering to these standards ensures consistency, readability, and maintainability in our codebase.


2. **DataFrame Naming : -**
* DataFrame variables should be named using descriptive and meaningful names.
* CamelCase naming convention is preferred for DataFrame variables.

3. **Column Naming : -**
* Columns in DataFrames should be named using lowercase with underscores for spaces.
* Columns should have clear and concise names, representing the information they contain.

4. **Indentation and Spacing : -**
* We use spaces for indentation.
* Avoid mixing tabs and spaces.
* Maintain consistent spacing around operators and after commas.

5. **Function and Method Calls : -**
* Function and method names follow camelCase naming convention.
* Use parentheses for function and method calls even if they don't require arguments.

6. **Comments Format : -**
* Comments should be used to explain code functionality, especially in complex or non-intuitive sections.
* Follow the format for comments:
* Name: Brief name of the function or code block.
* Description: Detailed explanation of the function or code block.
* Input: Parameters and their expected types.
* Output: Return values and their types.

7. **Handling Missing Data : -**
* Clearly document how missing data is handled in the code.
* Utilize appropriate methods for handling missing data based on the context, such as dropping, imputing, or marking missing values.

8. **Error Handling : -**
* Implement robust error handling to gracefully handle unexpected scenarios.
* Clearly document the expected errors and the actions taken to handle them.

9. **Code Review and Tools : -**

* All code undergoes thorough reviews, ensuring adherence to coding standards and best practices.
* Automated code review tools, such as AWS CodeGuru, are utilized to analyze and enhance code quality.
* CodeGuru provides insights into code improvements, identifies potential issues, and suggests optimizations.

<img width="768" alt="309627244-f851f1ac-20f9-45a9-bd17-04dbd8add2e0" src="https://github.com/user-attachments/assets/ab369db2-ebef-4c43-94a4-f2a4bfc2b10b" />

10. **Version Control  Hybrid Strategy : -**


* We follow a hybrid strategy combining elements of GitHub flow and trunk-based development.



![309627264-2e12a234-0e22-4b7e-8c8c-c1f1bb1574a8](https://github.com/user-attachments/assets/33b87706-0361-4368-92c2-259d930a151f)


**Kanban Board:**

1.**Kanban Board TODO list : -**

* New requirements or bugs are added to the Kanban board.
* Each requirement/bug is converted into an issue.

2.**Branching Strategy:**

* For each issue, a separate branch is created in the repository.
* Developers work on the created branch to implement the code for the specific requirement/bug.

3.**Pull Requests:**

* Code changes are pushed to the created branch.
* A pull request is submitted for code review.

4.**Testing:**

* After code review, the branch is merged with the test branch for testing.
* Testing is performed on the test branch.

5.**Production Deployment:**

* After successful testing, the code is merged with the production (prod) branch.
* The prod branch represents the stable and deployable version.
