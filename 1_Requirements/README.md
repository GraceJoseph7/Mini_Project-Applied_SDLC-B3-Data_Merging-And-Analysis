# Requirements

HIGH LEVEL REQUIREMENTS

| Requirement ID | Requirement Description |
| --- | --- |
| 1.Class average | To know the average of entire class in particular learning outcome. |
| 2.Student average | To know the average of each student in particular learning outcome. |
| 3. Class maxima | To know the maximum score of the class. |
| 4. Class minima | To know the minimum score of the class. |
| 5.Student maxima | To know the maximum score of the student. |
| 6.Student minima | To know the minimum score of the student. |

LOW LEVEL REQUIREMENTS

| Requirement ID | Requirement Description |
| --- | --- |
| 1.Top five data | To know the top 5 students of the class. |
| 2.Bottom five data | To know the bottom five data of the class. |


## Introduction
 --- TBD 

## Research
![Description](Link to Pic)
-- Content 
## Cost and Features
![Description](Link to Pic)
-- Content 
## Defining Our System
    -- TBD
## SWOT ANALYSIS
![SWOT-Sample](Link to Pic)

# 4W&#39;s and 1&#39;H

## Who:

**TBD**

## What:

**TBD**

## When:

**TBD**

## Where:

**TBD**

## How:

**TBD**

# Detail requirements
## High Level Requirements:
--- TBD in Tabular Format 
-- ID | Description | Status (Implemented/Future)


##  Low level Requirements:
--- TBD in Tabular Format 
-- ID | Description | Status (Implemented/Future)
=======

>>>>>>> 5d165d58a0fda3f5fb234f5b02769745e24fb757
>>>>>>> 
**LOW LEVEL TESTING:**

| TEST ID | TEST DECRIPTION | EXPECTED INPUT | EXPECTED OUTPUT | ACTUAL OUTPUT |
| --- | --- | --- | --- | --- |
| 1 | To check if mail-id not present (Requirement-based) | Enter empty mail id | Prompt asking for proper mail id and sending mail to a default mail id |
| 2 | To check if incorrect mail id is submitted (Scenario -based) | Enter a mail-id | Prompt displaying asking to enter right mail id |
| 3 | To check if marks obtained by student zero or not present (boundary-based) | empty values in input modules | Prompt displayed mentioning missing value and initially entering marks as 0 |

**HIGH LEVEL TESTING:**

| TEST ID | TEST DECRIPTION | EXPECTED INPUT | EXPECTED OUTPUT | ACTUAL OUTPUT |
| --- | --- | --- | --- | --- |
| 1 | To check if the statistical data obtained per record is sent to related stakeholders (Requirement-based) | Input modules with all values within boundaries | Statistical analysis for all inputs and emails are triggered |
| 2 | To check if marks obtained by a student exceeds the maximum score (Scenario-based) | Mark values of all students | Add the record to the end of the file and continue with further records |
| 3 | To check if the email id is not in proper format (Boundary-based) | Consolidated data | Add a default mail id and add it to end of the record |
