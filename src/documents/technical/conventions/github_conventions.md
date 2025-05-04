# Github Conventions

## Branches

### Sub-Branches

The GitHub repository uses different branches based on the type of work being performed:

- `functional` : For everything  that relate to project functionalities.
- `technical` : For all the technicalities of this project.
- `tests` : Principally the testing ground and test plan location.
- `dev` : the branch for project development.

### Main Branch

The `main` branch always contains the functioning code and reviewed documents. All work must go through review and pass required checks before being merged into main.

### Pull Requests

Pull request are mandatory to send content from sub-branches to the `main` branch. The pull request description must follow the [detailed commit conventions](#detailed-commit-conventions) below.
## File Organisation

### File and Folders Naming

Files and Folders should be written the same way using naming conventions 

| Object | Naming convention |
|--------|-------------------|
|Files | snake_case|
|Folders| flatcase|

### Folders Arrangement
A well-organized folder structure is essential for ensuring clear understanding of all file locations. 

Below is our file structure plan :
```
  ├── document/
  │     ├── functional/
  │     │   ├── functional_specification.md
  │     ├── management/
  │     │   ├── (All documents related to management)
  │     │   ├── monthly_reports/
  │     │   │   ├── monthly_report_1.md  
  │     ├── technical/
  │     │   ├── technical_specification.md  
  │     │   ├── conventions/
  │     │   │   ├── github_conventions.md  
  │     ├── tests/
  │     │   ├── technical_plan.md  
  │     │   ├── testfolder/
  │     │   │   ├── test1/ 
  │     |   │   │   ├── test_1_description
  │     |   │   │   ├── (code or system for the test to perform)
  │     ├── images/
  │     │   ├── functional_specification/
  │     │   │   ├── (any images related to functional  documents)
  │     │   ├── management/
  │     │   │   ├── (any images related to management documents)
  │     │   ├── technical_specification/
  │     │   │   ├── (any images related to technical documents)
  ├── src/
  │   ├── (all the files related to code are here, check the coding convention for a more detailed plan)
  ├── README.md

```
## Detailed Commit Conventions

All commits must render a detailed description of the content including :
- Any new document/code and whats their purpose for the project.
- Modifications to a document/code, precising where the modifications are and their purpose for the project.