MCQ Generation and Evaluation Pipeline

This project leverages LangChain and OpenAI's GPT-3.5-turbo to create and evaluate multiple-choice questions (MCQs) from a given text. The pipeline is designed to generate quizzes, analyze their complexity, and adjust them to fit the cognitive abilities of the intended student audience.

Features:

1. Automated MCQ Generation: Creates a set number of MCQs based on the input text.
2. Complexity Analysis: Evaluates the complexity of the generated questions to ensure they are appropriate for the target students.
3. Customizable Prompts: Allows customization of the number of questions, subject, and tone of the questions.

How It Works:

1. Text Input: The pipeline reads text from a specified file.
2. MCQ Generation: Using a predefined template, it generates MCQs.
3. Evaluation and Adjustment: Analyzes the complexity of the MCQs and adjusts them if necessary to ensure they match the cognitive abilities of the target students.
