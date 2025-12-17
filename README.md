1.A simple REST API built with *Flask* that performs basic arithmetic operations: addition, subtraction, multiplication, and division.

2. Features

- Add two numbers
- Subtract two numbers
- Multiply two numbers
- Divide two numbers (with division by zero handling)
- Returns JSON responses

3. Requirements

- Python 3.x
- Flask

You can install Flask using pip like this :

python -m pip install Flask

4.API Endpoint:-

'POST /calculate'
specifies the HTTP method and route users will call. 

5.Request body
{
  "x": 10,
  "y": 5,
  "operation": "add"
}
shows the expected JSON format for input.

6.Suppoerted Operations

"add" – Addition
"subtract" – Subtraction
"multiply" – Multiplication
"divide" – Division

7.Response Example

{
  "result": 15
}

8.Error Responses

-missing input
-Invalid numbers
-Division by Zero
-Invalid operation

9.HOW TO RUN

1. Clone the repository
2. Navigate to the project directory
3. Run the Flask app



