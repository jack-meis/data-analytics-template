# data-analytics-template

Template to use for data analytics projects

## Folders

#### Code

'code' folder has own README.md file

Sub-folders:

- notebooks: folder for all .ipynb files
- scripts: folder fro all .py files

#### Data

'data' folder has own README.md file

Sub-folders:

- cleaned: folder for all fully cleaned data
- original: all original data that is still in unmodified form
- processing: all data that is in the process of being cleaned
- raw: raw data that was scraped and has not undergone any cleaning

#### Reports

'reports' folder has own README.md file

Sub-folders:

- final: folder for all report final drafts
- initial: initial drafts for all reports

## Data Dictionary

Table that provides column names, data types, column descriptions for the features in the data

| Name            | Type    | Description                                             |
| --------------- | ------- | ------------------------------------------------------- |
| `Employee_ID`   | Integer | Unique identifier for each employee                     |
| `First_Name`    | String  | Employee's first name                                   |
| `Last_Name`     | String  | Employee's last name                                    |
| `Date_of_Birth` | Date    | Employee's birthdate                                    |
| `Email`         | String  | Employee's email address                                |
| `Salary`        | Float   | Employee's annual salary                                |
| `Department`    | String  | Department in which the employee works                  |
| `Start_Date`    | Date    | The date the employee started with the company          |
| `Is_Active`     | Boolean | Whether the employee is currently active (TRUE/FALSE)   |
| `Manager_ID`    | Integer | ID of the employee's manager (references `Employee_ID`) |

## To Do List

**List of project tasks that need to be completed**  
**Tasks should be crossed off once completed**

[ ] Update Data Dictionary  
[ ] Scrape Data from Web  
[ ] Clean Data  
[ ] Report Findings

## Change Log

All changes made should be reported in the CHANGELOG.md file  
New changes should be appended to the end of the CHANGELOG.md file
