# sumachel_math_practice
[amplify website] https://staging.d3viy4olsnhdnb.amplifyapp.com/ 
-  using python,  javascript,  html

GOAL: 
- web site thats accepts two inputs: max (M), number of problems (N)
- create N random problems [+ - * ÷ ] with the range of -M -> +M
- UI turns green for correct answer

Phase1
Create a lambda function
- [lambda_function.py](https://github.com/tjsiwinski2000/sumachel_math_practice/blob/main/lambda_function.py) 
- accepts two inputs: N, M
- returns M problems with solution e.g. 5 * 2,10 

Phase2
Connect lambda to API Gateway, Create Amplify site.
API-GATEWAY:   https://1z02i6c3v1.execute-api.us-west-1.amazonaws.com/dev
AMPLIFY SITE:  https://staging.dktvk9ol5owrw.amplifyapp.com/

Phase3
Create [index.html](https://github.com/tjsiwinski2000/sumachel_math_practice/blob/main/index.html) with javascript
Javascript callse the API-Gateway->Lambda
Display content on the webpage 
- e.g. 8 * -1 = []  -8


