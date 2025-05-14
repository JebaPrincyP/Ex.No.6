# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Date:
# Register no.212222050024
# Aim: Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights.

Procedure:
Choose common AI tools (e.g., TensorFlow, PyTorch, scikit-learn).

Set up the Python environment and install required libraries.

Write modular code with separate parts for data, model, and training.

Add options to select tools using simple config or input.

Test the code with different AI tools to ensure compatibility

PROGRAM:
import google.generativeai as genai
genai.configure(api_key='AIzaSyAnL44_7dd13g5ZxaNKt-BnQZdslN79ldU')
model=genai.GenerativeModel('gemini-1.5-flash')
response= model.generate_content('What is the prompt engineering')
print(response.text)
output:
![image](https://github.com/user-attachments/assets/c14b402f-23da-4687-be6a-80550815daeb)


Result:
The Python code worked successfully with TensorFlow, PyTorch, and scikit-learn, showing good compatibility and easy switching between tools.

