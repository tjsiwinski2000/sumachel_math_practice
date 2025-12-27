# sumachel_math_practice

GOAL: 
- [WEB SITE](https://staging.d3viy4olsnhdnb.amplifyapp.com/) thats accepts two inputs: max (M), number of problems (N)
- Create N random problems [+ - * ÷ ] with the range of -M -> +M
- UI turns green if correct answer entered
- Python,  Javascript,  HTML, AWS Amplify, Lambda

Phase1
Create the lambda function
- [lambda_function.py](https://github.com/tjsiwinski2000/sumachel_math_practice/blob/main/lambda_function.py) 
- accepts two inputs: N, M
- returns M problems with solution e.g. 5 * 2,10 

Phase2
- Connect lambda to [API-GATEWAY](https://1z02i6c3v1.execute-api.us-west-1.amazonaws.com/dev) 
- Create the [AMPLIFY SITE](https://staging.dktvk9ol5owrw.amplifyapp.com/) .

Phase3
- Create [index.html](https://github.com/tjsiwinski2000/sumachel_math_practice/blob/main/index.html) 
- Javascript in index.html-> API-Gateway -> Lambda -> displays content on the webpage 
- e.g. 8 * -1 = []  -8


