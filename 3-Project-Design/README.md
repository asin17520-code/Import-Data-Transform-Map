# 3. Project Design Phase

## System Architecture:
Excel File -> Load Data -> Import Set Table (Staging) -> Transform Map -> Target Table

## Field Mapping Design:
| Source Field (Excel) | Target Field | Coalesce |
| :--- | :--- | :--- |
| Name | name | No |
| Email | email | Yes |
| Department | department | No |
| Employee ID | employee_id | No |

## Flow Diagram: 
[Add your screenshot here]
