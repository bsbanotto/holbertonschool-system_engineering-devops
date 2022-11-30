This is a README for project 0x0E. API

There are 3 mandatory tasks in this project

Task 0 - Gather data from an API
 - Write a python script that returns information about a given employees TODO
 list progress
 - Must use urllib or requests module
 - Script must accept an integer as a parameter. This is the employee ID
 - Script must display TODO progress in this format
    - First line "Employee <EMPLOYEE_NAME> is done with tasks
    (<NUMBER_OF_DONE_TASKS>/<TOTAL_NUMBER_OF_TASKS>):
    - Second and `N` next lines display the title of completed tasks: 
         <TASK_TITLE> (1 tab and one space before task title)

Task 1 - Export to CSV
 - Using task 0, extend the script to export data in CSV format
    - Records all tasks that are owned by this employee
    - Format must be "USER_ID", "USERNAME", "TASK_COMPLETED_STATUS",
    "TASK_TITLE"
    - File name must be: USER_ID.csv

Task 2 - Export to JSON
 - Using task 0, extend the script to export data in JSON format
    - Records all tasks that are owned by this employee
    - Format must be { "USER_ID": [{"task": "TASK_TITLE",
    "completed": TASK_COMPLETED_STATUS, "username": "USERNAME"},
    {"task": "TASK_TITLE", "completed": TASK_COMPLETED_STATUS,
    "username": "USERNAME"}, ... ]}
    - File name must be: USER_ID.json
