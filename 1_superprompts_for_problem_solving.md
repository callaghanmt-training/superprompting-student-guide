# 1. SuperPrompts for Problem Solving in STEM

Large language models like ChatGPT can be invaluable tools for solving complex problems in STEM subjects, such as mathematical equations, programming challenges, and engineering tasks. 

This one-page guide will focus on writing effective prompts to assist students in tackling these problems using LLMs.

## Tips for Crafting Problem Solving Prompts

1. **Identify the Problem**: Clearly state the problem you need to solve, specifying any relevant parameters or constraints.

2. **Provide Context**: Offer sufficient background information and context to ensure the model understands the problem's domain and requirements.

3. **Specify the Desired Solution Format**: Clearly indicate the format you want the solution in, such as step-by-step instructions, graphs (this is a bit tricky, but by specifying a format such as DOT or Mermaid, GPT can give you tge structure of a diagram), equations, or code snippets.

4. **Request Explanations**: Ask the model to explain its reasoning, calculations, or steps taken to arrive at the solution. This will help you understand the underlying concepts and enhance your learning experience.

5. **Enquire about Alternative Solutions**: Encourage the model to explore alternative approaches or solutions to the problem, helping you gain a deeper understanding of the subject matter.

---

### Example SuperPrompts:

#### Mathematics:

Objective: Solve a calculus problem.

Prompt: Calculate the derivative of the function f(x) = x^3 - 4x^2 + 2x with respect to x. Provide a step-by-step explanation of the process and the final simplified derivative.

#### Programming:

Objective: Debug a Python code snippet.

Prompt: The following Python code snippet is intended to calculate the factorial of a given positive integer 'n'. However, it contains an error. Identify the error, provide a corrected version of the code, and explain the changes you made.

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n)
```
#### Engineering:

Objective: Understand the concept of stress and strain in materials.

Prompt: Explain the relationship between stress and strain in elastic materials. Describe Hooke's Law and provide the relevant equation. Discuss the significance of the Young's modulus and how it can be used to characterise a material's elasticity. Include at least one reputable source to support your explanation.
