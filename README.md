Frontend Developer Assignment (React & Bootstrap)
Objective:
Create a web-based Expression Engine UI using Bootstrap and React
Requirements:
Use Bootstrap for styling to ensure a responsive and visually appealing UI.
Implement a form where users can 
input connector type: AND/OR
input expressions. Every expressions contains following fields
Dropdown: Rule Type with values - Age, Credit Score, Account Balance
Operator: >, <, ≥, ≤, =
Value
Score
User should be able to add and delete expressions.
Expected Output:
{
    "rules": [
          {
            "key": "age",
            "output": {
                "value": 60,
                "operator": ">=",
                "score": 50
            },
        },
        {
            "key": "age",
            "output": {
                "value": 40,
                "operator": ">=",
                "score": 100
            }
        },
        {
            "key": "account_balance",
            "output": {
                "value": 100000,
                "operator": ">=",
                "score": 200
            },
        },
    ],
    "combinator": "and"
}
